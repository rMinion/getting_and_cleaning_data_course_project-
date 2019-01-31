# Data Descrption

## From orignal file: 

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

tBodyAcc-XYZ
tGravityAcc-XYZ
tBodyAccJerk-XYZ
tBodyGyro-XYZ
tBodyGyroJerk-XYZ
tBodyAccMag
tGravityAccMag
tBodyAccJerkMag
tBodyGyroMag
tBodyGyroJerkMag
fBodyAcc-XYZ
fBodyAccJerk-XYZ
fBodyGyro-XYZ
fBodyAccMag
fBodyAccJerkMag
fBodyGyroMag
fBodyGyroJerkMag

The set of variables that were estimated from these signals are: 

mean(): Mean value
std(): Standard deviation

The complete list of variables of each feature vector is available below:

| Variable name  | Original variable | Class |
| ------------- | ------------- | ------------- |
|tBodyAcc-mean-Y|tBodyAcc-mean()-Y|numeric|
|tBodyAcc-mean-Z|tBodyAcc-mean()-Z|numeric|
|tBodyAcc-std-X|tBodyAcc-std()-X|numeric|
|tBodyAcc-std-Y|tBodyAcc-std()-Y|numeric|
|tBodyAcc-std-Z|tBodyAcc-std()-Z|numeric|
|tGravityAcc-mean-X|tGravityAcc-mean()-X|numeric|
|tGravityAcc-mean-Y|tGravityAcc-mean()-Y|numeric|
|tGravityAcc-mean-Z|tGravityAcc-mean()-Z|numeric|
|tGravityAcc-std-X|tGravityAcc-std()-X|numeric|
|tGravityAcc-std-Y|tGravityAcc-std()-Y|numeric|
|tGravityAcc-std-Z|tGravityAcc-std()-Z|numeric|
|tBodyAccJerk-mean-X|tBodyAccJerk-mean()-X|numeric|
|tBodyAccJerk-mean-Y|tBodyAccJerk-mean()-Y|numeric|
|tBodyAccJerk-mean-Z|tBodyAccJerk-mean()-Z|numeric|
|tBodyAccJerk-std-X|tBodyAccJerk-std()-X|numeric|
|tBodyAccJerk-std-Y|tBodyAccJerk-std()-Y|numeric|
|tBodyAccJerk-std-Z|tBodyAccJerk-std()-Z|numeric|
|tBodyGyro-mean-X|tBodyGyro-mean()-X|numeric|
|tBodyGyro-mean-Y|tBodyGyro-mean()-Y|numeric|
|tBodyGyro-mean-Z|tBodyGyro-mean()-Z|numeric|
|tBodyGyro-std-X|tBodyGyro-std()-X|numeric|
|tBodyGyro-std-Y|tBodyGyro-std()-Y|numeric|
|tBodyGyro-std-Z|tBodyGyro-std()-Z|numeric|
|tBodyGyroJerk-mean-X|tBodyGyroJerk-mean()-X|numeric|
|tBodyGyroJerk-mean-Y|tBodyGyroJerk-mean()-Y|numeric|
|tBodyGyroJerk-mean-Z|tBodyGyroJerk-mean()-Z|numeric|
|tBodyGyroJerk-std-X|tBodyGyroJerk-std()-X|numeric|
|tBodyGyroJerk-std-Y|tBodyGyroJerk-std()-Y|numeric|
|tBodyGyroJerk-std-Z|tBodyGyroJerk-std()-Z|numeric|
|tBodyAccMag-mean|tBodyAccMag-mean()|numeric|
|tBodyAccMag-std|tBodyAccMag-std()|numeric|
|tGravityAccMag-mean|tGravityAccMag-mean()|numeric|
|tGravityAccMag-std|tGravityAccMag-std()|numeric|
|tBodyAccJerkMag-mean|tBodyAccJerkMag-mean()|numeric|
|tBodyAccJerkMag-std|tBodyAccJerkMag-std()|numeric|
|tBodyGyroMag-mean|tBodyGyroMag-mean()|numeric|
|tBodyGyroMag-std|tBodyGyroMag-std()|numeric|
|tBodyGyroJerkMag-mean|tBodyGyroJerkMag-mean()|numeric|
|tBodyGyroJerkMag-std|tBodyGyroJerkMag-std()|numeric|
|fBodyAcc-mean-X|fBodyAcc-mean()-X|numeric|
|fBodyAcc-mean-Y|fBodyAcc-mean()-Y|numeric|
|fBodyAcc-mean-Z|fBodyAcc-mean()-Z|numeric|
|fBodyAcc-std-X|fBodyAcc-std()-X|numeric|
|fBodyAcc-std-Y|fBodyAcc-std()-Y|numeric|
|fBodyAcc-std-Z|fBodyAcc-std()-Z|numeric|
|fBodyAcc-meanFreq-X|fBodyAcc-meanFreq()-X|numeric|
|fBodyAcc-meanFreq-Y|fBodyAcc-meanFreq()-Y|numeric|
|fBodyAcc-meanFreq-Z|fBodyAcc-meanFreq()-Z|numeric|
|fBodyAccJerk-mean-X|fBodyAccJerk-mean()-X|numeric|
|fBodyAccJerk-mean-Y|fBodyAccJerk-mean()-Y|numeric|
|fBodyAccJerk-mean-Z|fBodyAccJerk-mean()-Z|numeric|
|fBodyAccJerk-std-X|fBodyAccJerk-std()-X|numeric|
|fBodyAccJerk-std-Y|fBodyAccJerk-std()-Y|numeric|
|fBodyAccJerk-std-Z|fBodyAccJerk-std()-Z|numeric|
|fBodyAccJerk-meanFreq-X|fBodyAccJerk-meanFreq()-X|numeric|
|fBodyAccJerk-meanFreq-Y|fBodyAccJerk-meanFreq()-Y|numeric|
|fBodyAccJerk-meanFreq-Z|fBodyAccJerk-meanFreq()-Z|numeric|
|fBodyGyro-mean-X|fBodyGyro-mean()-X|numeric|
|fBodyGyro-mean-Y|fBodyGyro-mean()-Y|numeric|
|fBodyGyro-mean-Z|fBodyGyro-mean()-Z|numeric|
|fBodyGyro-std-X|fBodyGyro-std()-X|numeric|
|fBodyGyro-std-Y|fBodyGyro-std()-Y|numeric|
|fBodyGyro-std-Z|fBodyGyro-std()-Z|numeric|
|fBodyGyro-meanFreq-X|fBodyGyro-meanFreq()-X|numeric|
|fBodyGyro-meanFreq-Y|fBodyGyro-meanFreq()-Y|numeric|
|fBodyGyro-meanFreq-Z|fBodyGyro-meanFreq()-Z|numeric|
|fBodyAccMag-mean|fBodyAccMag-mean()|numeric|
|fBodyAccMag-std|fBodyAccMag-std()|numeric|
|fBodyAccMag-meanFreq|fBodyAccMag-meanFreq()|numeric|
|fBodyBodyAccJerkMag-mean|fBodyBodyAccJerkMag-mean()|numeric|
|fBodyBodyAccJerkMag-std|fBodyBodyAccJerkMag-std()|numeric|
|fBodyBodyAccJerkMag-meanFreq|fBodyBodyAccJerkMag-meanFreq()|numeric|
|fBodyBodyGyroMag-mean|fBodyBodyGyroMag-mean()|numeric|
|fBodyBodyGyroMag-std|fBodyBodyGyroMag-std()|numeric|
|fBodyBodyGyroMag-meanFreq|fBodyBodyGyroMag-meanFreq()|numeric|
|fBodyBodyGyroJerkMag-mean|fBodyBodyGyroJerkMag-mean()|numeric|
|fBodyBodyGyroJerkMag-std|fBodyBodyGyroJerkMag-std()|numeric|
|fBodyBodyGyroJerkMag-meanFreq|fBodyBodyGyroJerkMag-meanFreq()|numeric|



