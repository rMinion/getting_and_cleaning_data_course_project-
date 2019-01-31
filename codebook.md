### From orignal file:

The features selected for this database come from the accelerometer and
gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain
signals (prefix 't' to denote time) were captured at a constant rate of
50 Hz. Then they were filtered using a median filter and a 3rd order low
pass Butterworth filter with a corner frequency of 20 Hz to remove
noise. Similarly, the acceleration signal was then separated into body
and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ)
using another low pass Butterworth filter with a corner frequency of 0.3
Hz.

Subsequently, the body linear acceleration and angular velocity were
derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and
tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional
signals were calculated using the Euclidean norm (tBodyAccMag,
tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).

Finally a Fast Fourier Transform (FFT) was applied to some of these
signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ,
fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to
indicate frequency domain signals).

These signals were used to estimate variables of the feature vector for
each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

-   tBodyAcc-XYZ
-   tGravityAcc-XYZ
-   tBodyAccJerk-XYZ
-   tBodyGyro-XYZ
-   tBodyGyroJerk-XYZ
-   tBodyAccMag
-   tGravityAccMag
-   tBodyAccJerkMag
-   tBodyGyroMag
-   tBodyGyroJerkMag
-   fBodyAcc-XYZ
-   fBodyAccJerk-XYZ
-   fBodyGyro-XYZ
-   fBodyAccMag
-   fBodyAccJerkMag
-   fBodyGyroMag
-   fBodyGyroJerkMag

The set of variables that were estimated from these signals are:

mean(): Mean value std(): Standard deviation

The complete list of variables of each feature vector is available below:
-------------------------------------------------------------------------

<table style="width:78%;">
<colgroup>
<col width="19%" />
<col width="19%" />
<col width="19%" />
<col width="19%" />
</colgroup>
<thead>
<tr class="header">
<th>No.</th>
<th>Variable name</th>
<th>Original variable</th>
<th>Class</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td>subject</td>
<td>person id</td>
<td>integer</td>
</tr>
<tr class="even">
<td>2</td>
<td>activity</td>
<td>one of six activity ( 1-walking, 2-walking_upstairs, 3-walking_downstairs, 4-sitting, 5-standing, 6-laying)</td>
<td>factor</td>
</tr>
<tr class="odd">
<td>3</td>
<td>tBodyAcc-mean-X</td>
<td>tBodyAcc-mean()-X</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>4</td>
<td>tBodyAcc-mean-Y</td>
<td>tBodyAcc-mean()-Y</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>5</td>
<td>tBodyAcc-mean-Z</td>
<td>tBodyAcc-mean()-Z</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>6</td>
<td>tBodyAcc-std-X</td>
<td>tBodyAcc-std()-X</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>7</td>
<td>tBodyAcc-std-Y</td>
<td>tBodyAcc-std()-Y</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>8</td>
<td>tBodyAcc-std-Z</td>
<td>tBodyAcc-std()-Z</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>9</td>
<td>tGravityAcc-mean-X</td>
<td>tGravityAcc-mean()-X</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>10</td>
<td>tGravityAcc-mean-Y</td>
<td>tGravityAcc-mean()-Y</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>11</td>
<td>tGravityAcc-mean-Z</td>
<td>tGravityAcc-mean()-Z</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>12</td>
<td>tGravityAcc-std-X</td>
<td>tGravityAcc-std()-X</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>13</td>
<td>tGravityAcc-std-Y</td>
<td>tGravityAcc-std()-Y</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>14</td>
<td>tGravityAcc-std-Z</td>
<td>tGravityAcc-std()-Z</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>15</td>
<td>tBodyAccJerk-mean-X</td>
<td>tBodyAccJerk-mean()-X</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>16</td>
<td>tBodyAccJerk-mean-Y</td>
<td>tBodyAccJerk-mean()-Y</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>17</td>
<td>tBodyAccJerk-mean-Z</td>
<td>tBodyAccJerk-mean()-Z</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>18</td>
<td>tBodyAccJerk-std-X</td>
<td>tBodyAccJerk-std()-X</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>19</td>
<td>tBodyAccJerk-std-Y</td>
<td>tBodyAccJerk-std()-Y</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>20</td>
<td>tBodyAccJerk-std-Z</td>
<td>tBodyAccJerk-std()-Z</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>21</td>
<td>tBodyGyro-mean-X</td>
<td>tBodyGyro-mean()-X</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>22</td>
<td>tBodyGyro-mean-Y</td>
<td>tBodyGyro-mean()-Y</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>23</td>
<td>tBodyGyro-mean-Z</td>
<td>tBodyGyro-mean()-Z</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>24</td>
<td>tBodyGyro-std-X</td>
<td>tBodyGyro-std()-X</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>25</td>
<td>tBodyGyro-std-Y</td>
<td>tBodyGyro-std()-Y</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>26</td>
<td>tBodyGyro-std-Z</td>
<td>tBodyGyro-std()-Z</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>27</td>
<td>tBodyGyroJerk-mean-X</td>
<td>tBodyGyroJerk-mean()-X</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>28</td>
<td>tBodyGyroJerk-mean-Y</td>
<td>tBodyGyroJerk-mean()-Y</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>29</td>
<td>tBodyGyroJerk-mean-Z</td>
<td>tBodyGyroJerk-mean()-Z</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>30</td>
<td>tBodyGyroJerk-std-X</td>
<td>tBodyGyroJerk-std()-X</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>31</td>
<td>tBodyGyroJerk-std-Y</td>
<td>tBodyGyroJerk-std()-Y</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>32</td>
<td>tBodyGyroJerk-std-Z</td>
<td>tBodyGyroJerk-std()-Z</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>33</td>
<td>tBodyAccMag-mean</td>
<td>tBodyAccMag-mean()</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>34</td>
<td>tBodyAccMag-std</td>
<td>tBodyAccMag-std()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>35</td>
<td>tGravityAccMag-mean</td>
<td>tGravityAccMag-mean()</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>36</td>
<td>tGravityAccMag-std</td>
<td>tGravityAccMag-std()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>37</td>
<td>tBodyAccJerkMag-mean</td>
<td>tBodyAccJerkMag-mean()</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>38</td>
<td>tBodyAccJerkMag-std</td>
<td>tBodyAccJerkMag-std()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>39</td>
<td>tBodyGyroMag-mean</td>
<td>tBodyGyroMag-mean()</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>40</td>
<td>tBodyGyroMag-std</td>
<td>tBodyGyroMag-std()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>41</td>
<td>tBodyGyroJerkMag-mean</td>
<td>tBodyGyroJerkMag-mean()</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>42</td>
<td>tBodyGyroJerkMag-std</td>
<td>tBodyGyroJerkMag-std()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>43</td>
<td>fBodyAcc-mean-X</td>
<td>fBodyAcc-mean()-X</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>44</td>
<td>fBodyAcc-mean-Y</td>
<td>fBodyAcc-mean()-Y</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>45</td>
<td>fBodyAcc-mean-Z</td>
<td>fBodyAcc-mean()-Z</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>46</td>
<td>fBodyAcc-std-X</td>
<td>fBodyAcc-std()-X</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>47</td>
<td>fBodyAcc-std-Y</td>
<td>fBodyAcc-std()-Y</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>48</td>
<td>fBodyAcc-std-Z</td>
<td>fBodyAcc-std()-Z</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>49</td>
<td>fBodyAcc-meanFreq-X</td>
<td>fBodyAcc-meanFreq()-X</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>50</td>
<td>fBodyAcc-meanFreq-Y</td>
<td>fBodyAcc-meanFreq()-Y</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>51</td>
<td>fBodyAcc-meanFreq-Z</td>
<td>fBodyAcc-meanFreq()-Z</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>52</td>
<td>fBodyAccJerk-mean-X</td>
<td>fBodyAccJerk-mean()-X</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>53</td>
<td>fBodyAccJerk-mean-Y</td>
<td>fBodyAccJerk-mean()-Y</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>54</td>
<td>fBodyAccJerk-mean-Z</td>
<td>fBodyAccJerk-mean()-Z</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>55</td>
<td>fBodyAccJerk-std-X</td>
<td>fBodyAccJerk-std()-X</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>56</td>
<td>fBodyAccJerk-std-Y</td>
<td>fBodyAccJerk-std()-Y</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>57</td>
<td>fBodyAccJerk-std-Z</td>
<td>fBodyAccJerk-std()-Z</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>58</td>
<td>fBodyAccJerk-meanFreq-X</td>
<td>fBodyAccJerk-meanFreq()-X</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>59</td>
<td>fBodyAccJerk-meanFreq-Y</td>
<td>fBodyAccJerk-meanFreq()-Y</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>60</td>
<td>fBodyAccJerk-meanFreq-Z</td>
<td>fBodyAccJerk-meanFreq()-Z</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>61</td>
<td>fBodyGyro-mean-X</td>
<td>fBodyGyro-mean()-X</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>62</td>
<td>fBodyGyro-mean-Y</td>
<td>fBodyGyro-mean()-Y</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>63</td>
<td>fBodyGyro-mean-Z</td>
<td>fBodyGyro-mean()-Z</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>64</td>
<td>fBodyGyro-std-X</td>
<td>fBodyGyro-std()-X</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>65</td>
<td>fBodyGyro-std-Y</td>
<td>fBodyGyro-std()-Y</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>66</td>
<td>fBodyGyro-std-Z</td>
<td>fBodyGyro-std()-Z</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>67</td>
<td>fBodyGyro-meanFreq-X</td>
<td>fBodyGyro-meanFreq()-X</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>68</td>
<td>fBodyGyro-meanFreq-Y</td>
<td>fBodyGyro-meanFreq()-Y</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>69</td>
<td>fBodyGyro-meanFreq-Z</td>
<td>fBodyGyro-meanFreq()-Z</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>70</td>
<td>fBodyAccMag-mean</td>
<td>fBodyAccMag-mean()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>71</td>
<td>fBodyAccMag-std</td>
<td>fBodyAccMag-std()</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>72</td>
<td>fBodyAccMag-meanFreq</td>
<td>fBodyAccMag-meanFreq()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>73</td>
<td>fBodyBodyAccJerkMag-mean</td>
<td>fBodyBodyAccJerkMag-mean()</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>74</td>
<td>fBodyBodyAccJerkMag-std</td>
<td>fBodyBodyAccJerkMag-std()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>75</td>
<td>fBodyBodyAccJerkMag-meanFreq</td>
<td>fBodyBodyAccJerkMag-meanFreq()</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>76</td>
<td>fBodyBodyGyroMag-mean</td>
<td>fBodyBodyGyroMag-mean()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>77</td>
<td>fBodyBodyGyroMag-std</td>
<td>fBodyBodyGyroMag-std()</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>78</td>
<td>fBodyBodyGyroMag-meanFreq</td>
<td>fBodyBodyGyroMag-meanFreq()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>79</td>
<td>fBodyBodyGyroJerkMag-mean</td>
<td>fBodyBodyGyroJerkMag-mean()</td>
<td>numeric</td>
</tr>
<tr class="even">
<td>80</td>
<td>fBodyBodyGyroJerkMag-std</td>
<td>fBodyBodyGyroJerkMag-std()</td>
<td>numeric</td>
</tr>
<tr class="odd">
<td>81</td>
<td>fBodyBodyGyroJerkMag-meanFreq</td>
<td>fBodyBodyGyroJerkMag-meanFreq()</td>
<td>numeric</td>
</tr>
</tbody>
</table>

    final_data_set<-read.table(file = "final_data_set.txt", sep=" ", dec=".", header = TRUE,colClasses = c("integer", "factor", rep("numeric", 79)))
    str(final_data_set)

    ## 'data.frame':    180 obs. of  81 variables:
    ##  $ subject                      : int  1 1 1 1 1 1 10 10 10 10 ...
    ##  $ activity                     : Factor w/ 6 levels "laying","sitting",..: 4 6 5 2 3 1 4 6 5 2 ...
    ##  $ tBodyAcc_mean_X              : num  0.277 0.255 0.289 0.261 0.279 ...
    ##  $ tBodyAcc_mean_Y              : num  -0.01738 -0.02395 -0.00992 -0.00131 -0.01614 ...
    ##  $ tBodyAcc_mean_Z              : num  -0.1111 -0.0973 -0.1076 -0.1045 -0.1106 ...
    ##  $ tBodyAcc_std_X               : num  -0.284 -0.355 0.03 -0.977 -0.996 ...
    ##  $ tBodyAcc_std_Y               : num  0.11446 -0.00232 -0.03194 -0.92262 -0.97319 ...
    ##  $ tBodyAcc_std_Z               : num  -0.26 -0.0195 -0.2304 -0.9396 -0.9798 ...
    ##  $ tGravityAcc_mean_X           : num  0.935 0.893 0.932 0.832 0.943 ...
    ##  $ tGravityAcc_mean_Y           : num  -0.282 -0.362 -0.267 0.204 -0.273 ...
    ##  $ tGravityAcc_mean_Z           : num  -0.0681 -0.0754 -0.0621 0.332 0.0135 ...
    ##  $ tGravityAcc_std_X            : num  -0.977 -0.956 -0.951 -0.968 -0.994 ...
    ##  $ tGravityAcc_std_Y            : num  -0.971 -0.953 -0.937 -0.936 -0.981 ...
    ##  $ tGravityAcc_std_Z            : num  -0.948 -0.912 -0.896 -0.949 -0.976 ...
    ##  $ tBodyAccJerk_mean_X          : num  0.074 0.1014 0.0542 0.0775 0.0754 ...
    ##  $ tBodyAccJerk_mean_Y          : num  0.028272 0.019486 0.02965 -0.000619 0.007976 ...
    ##  $ tBodyAccJerk_mean_Z          : num  -0.00417 -0.04556 -0.01097 -0.00337 -0.00369 ...
    ##  $ tBodyAccJerk_std_X           : num  -0.1136 -0.4468 -0.0123 -0.9864 -0.9946 ...
    ##  $ tBodyAccJerk_std_Y           : num  0.067 -0.378 -0.102 -0.981 -0.986 ...
    ##  $ tBodyAccJerk_std_Z           : num  -0.503 -0.707 -0.346 -0.988 -0.992 ...
    ##  $ tBodyGyro_mean_X             : num  -0.0418 0.0505 -0.0351 -0.0454 -0.024 ...
    ##  $ tBodyGyro_mean_Y             : num  -0.0695 -0.1662 -0.0909 -0.0919 -0.0594 ...
    ##  $ tBodyGyro_mean_Z             : num  0.0849 0.0584 0.0901 0.0629 0.0748 ...
    ##  $ tBodyGyro_std_X              : num  -0.474 -0.545 -0.458 -0.977 -0.987 ...
    ##  $ tBodyGyro_std_Y              : num  -0.05461 0.00411 -0.12635 -0.96647 -0.98773 ...
    ##  $ tBodyGyro_std_Z              : num  -0.344 -0.507 -0.125 -0.941 -0.981 ...
    ##  $ tBodyGyroJerk_mean_X         : num  -0.09 -0.1222 -0.074 -0.0937 -0.0996 ...
    ##  $ tBodyGyroJerk_mean_Y         : num  -0.0398 -0.0421 -0.044 -0.0402 -0.0441 ...
    ##  $ tBodyGyroJerk_mean_Z         : num  -0.0461 -0.0407 -0.027 -0.0467 -0.049 ...
    ##  $ tBodyGyroJerk_std_X          : num  -0.207 -0.615 -0.487 -0.992 -0.993 ...
    ##  $ tBodyGyroJerk_std_Y          : num  -0.304 -0.602 -0.239 -0.99 -0.995 ...
    ##  $ tBodyGyroJerk_std_Z          : num  -0.404 -0.606 -0.269 -0.988 -0.992 ...
    ##  $ tBodyAccMag_mean             : num  -0.137 -0.1299 0.0272 -0.9485 -0.9843 ...
    ##  $ tBodyAccMag_std              : num  -0.2197 -0.325 0.0199 -0.9271 -0.9819 ...
    ##  $ tGravityAccMag_mean          : num  -0.137 -0.1299 0.0272 -0.9485 -0.9843 ...
    ##  $ tGravityAccMag_std           : num  -0.2197 -0.325 0.0199 -0.9271 -0.9819 ...
    ##  $ tBodyAccJerkMag_mean         : num  -0.1414 -0.4665 -0.0894 -0.9874 -0.9924 ...
    ##  $ tBodyAccJerkMag_std          : num  -0.0745 -0.479 -0.0258 -0.9841 -0.9931 ...
    ##  $ tBodyGyroMag_mean            : num  -0.161 -0.1267 -0.0757 -0.9309 -0.9765 ...
    ##  $ tBodyGyroMag_std             : num  -0.187 -0.149 -0.226 -0.935 -0.979 ...
    ##  $ tBodyGyroJerkMag_mean        : num  -0.299 -0.595 -0.295 -0.992 -0.995 ...
    ##  $ tBodyGyroJerkMag_std         : num  -0.325 -0.649 -0.307 -0.988 -0.995 ...
    ##  $ fBodyAcc_mean_X              : num  -0.2028 -0.4043 0.0382 -0.9796 -0.9952 ...
    ##  $ fBodyAcc_mean_Y              : num  0.08971 -0.19098 0.00155 -0.94408 -0.97707 ...
    ##  $ fBodyAcc_mean_Z              : num  -0.332 -0.433 -0.226 -0.959 -0.985 ...
    ##  $ fBodyAcc_std_X               : num  -0.3191 -0.3374 0.0243 -0.9764 -0.996 ...
    ##  $ fBodyAcc_std_Y               : num  0.056 0.0218 -0.113 -0.9173 -0.9723 ...
    ##  $ fBodyAcc_std_Z               : num  -0.28 0.086 -0.298 -0.934 -0.978 ...
    ##  $ fBodyAcc_meanFreq_X          : num  -0.2075 -0.4187 -0.3074 -0.0495 0.0865 ...
    ##  $ fBodyAcc_meanFreq_Y          : num  0.1131 -0.1607 0.0632 0.0759 0.1175 ...
    ##  $ fBodyAcc_meanFreq_Z          : num  0.0497 -0.5201 0.2943 0.2388 0.2449 ...
    ##  $ fBodyAccJerk_mean_X          : num  -0.1705 -0.4799 -0.0277 -0.9866 -0.9946 ...
    ##  $ fBodyAccJerk_mean_Y          : num  -0.0352 -0.4134 -0.1287 -0.9816 -0.9854 ...
    ##  $ fBodyAccJerk_mean_Z          : num  -0.469 -0.685 -0.288 -0.986 -0.991 ...
    ##  $ fBodyAccJerk_std_X           : num  -0.1336 -0.4619 -0.0863 -0.9875 -0.9951 ...
    ##  $ fBodyAccJerk_std_Y           : num  0.107 -0.382 -0.135 -0.983 -0.987 ...
    ##  $ fBodyAccJerk_std_Z           : num  -0.535 -0.726 -0.402 -0.988 -0.992 ...
    ##  $ fBodyAccJerk_meanFreq_X      : num  -0.209 -0.377 -0.253 0.257 0.314 ...
    ##  $ fBodyAccJerk_meanFreq_Y      : num  -0.3862 -0.5095 -0.3376 0.0475 0.0392 ...
    ##  $ fBodyAccJerk_meanFreq_Z      : num  -0.18553 -0.5511 0.00937 0.09239 0.13858 ...
    ##  $ fBodyGyro_mean_X             : num  -0.339 -0.493 -0.352 -0.976 -0.986 ...
    ##  $ fBodyGyro_mean_Y             : num  -0.1031 -0.3195 -0.0557 -0.9758 -0.989 ...
    ##  $ fBodyGyro_mean_Z             : num  -0.2559 -0.4536 -0.0319 -0.9513 -0.9808 ...
    ##  $ fBodyGyro_std_X              : num  -0.517 -0.566 -0.495 -0.978 -0.987 ...
    ##  $ fBodyGyro_std_Y              : num  -0.0335 0.1515 -0.1814 -0.9623 -0.9871 ...
    ##  $ fBodyGyro_std_Z              : num  -0.437 -0.572 -0.238 -0.944 -0.982 ...
    ##  $ fBodyGyro_meanFreq_X         : num  0.0148 -0.1875 -0.1005 0.1892 -0.1203 ...
    ##  $ fBodyGyro_meanFreq_Y         : num  -0.0658 -0.4736 0.0826 0.0631 -0.0447 ...
    ##  $ fBodyGyro_meanFreq_Z         : num  0.000773 -0.133374 -0.075676 -0.029784 0.100608 ...
    ##  $ fBodyAccMag_mean             : num  -0.1286 -0.3524 0.0966 -0.9478 -0.9854 ...
    ##  $ fBodyAccMag_std              : num  -0.398 -0.416 -0.187 -0.928 -0.982 ...
    ##  $ fBodyAccMag_meanFreq         : num  0.1906 -0.0977 0.1192 0.2367 0.2846 ...
    ##  $ fBodyBodyAccJerkMag_mean     : num  -0.0571 -0.4427 0.0262 -0.9853 -0.9925 ...
    ##  $ fBodyBodyAccJerkMag_std      : num  -0.103 -0.533 -0.104 -0.982 -0.993 ...
    ##  $ fBodyBodyAccJerkMag_meanFreq : num  0.0938 0.0854 0.0765 0.3519 0.4222 ...
    ##  $ fBodyBodyGyroMag_mean        : num  -0.199 -0.326 -0.186 -0.958 -0.985 ...
    ##  $ fBodyBodyGyroMag_std         : num  -0.321 -0.183 -0.398 -0.932 -0.978 ...
    ##  $ fBodyBodyGyroMag_meanFreq    : num  0.268844 -0.219303 0.349614 -0.000262 -0.028606 ...
    ##  $ fBodyBodyGyroJerkMag_mean    : num  -0.319 -0.635 -0.282 -0.99 -0.995 ...
    ##  $ fBodyBodyGyroJerkMag_std     : num  -0.382 -0.694 -0.392 -0.987 -0.995 ...
    ##  $ fBodyBodyGyroJerkMag_meanFreq: num  0.191 0.114 0.19 0.185 0.334 ...
