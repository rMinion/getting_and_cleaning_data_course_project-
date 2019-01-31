# getting_and_cleaning_data_course_project-

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set.

The srcipt works as fallows: 

### 0. Preparation: downloading data files from web-source, unzip it to working directory, create object for each data file separate for training and test data
```
##Download file
download.file(url = "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip", destfile = "data.zip", mode = "wb")
##Unzip folder containing data
unzip(zipfile = "data.zip")
#train data set
X_train<-read.table("./UCI HAR Dataset/train/X_train.txt")
subject_train<-readLines("./UCI HAR Dataset/train/subject_train.txt")
labels_train<-readLines("./UCI HAR Dataset/train/y_train.txt")
#test data set
X_test<-read.table("./UCI HAR Dataset/test/X_test.txt")
subject_test<-readLines("./UCI HAR Dataset/test/subject_test.txt")
labels_test<-readLines("./UCI HAR Dataset/test/y_test.txt")
```
### 1.Merges the training and the test sets to create one data set.
```
data<-rbind(X_train,X_test)
```
### 2.Extracts only the measurements on the mean and standard deviation for each measurement.
```
features<-readLines("./UCI HAR Dataset/features.txt")
selected_features<-grep(pattern = "mean|std", x = features)
data<-data[,selected_features]
```
### 3.Uses descriptive activity names to name the activities in the data set
```
data$activity<-factor(x = c(labels_train, labels_test), levels = c(1,2,3,4,5,6), labels = c("walking", "walking_upstairs","walking_downstairs","sitting","standing","laying"))
data$subject<-c(subject_train, subject_test)
```
### 4.Appropriately labels the data set with descriptive variable names.
```
nice_colnames<-grep(pattern = "mean|std", x = features, value = TRUE)
nice_colnames<-gsub(pattern = "\\(\\)|[0-9]+| | ", replacement = "", x = nice_colnames)
nice_colnames<-gsub(pattern = "-", replacement = "_", x = nice_colnames)
colnames(data)<-c(nice_colnames, "activity", "subject")
```
### 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
```
library(dplyr)
final_data_set<-data %>% 
  group_by(subject, activity) %>%
  summarise_all(mean)
```
write.table(x = final_data_set, file = "final_data_set.txt", row.names = FALSE, quote = FALSE)
