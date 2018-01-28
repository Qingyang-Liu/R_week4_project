Description of the variables and the data

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

'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.
't' is used to denote time
'f' is used to denote frequence

Additional vectors obtained by averaging the signals in a signal window sample.

gravityMean
tBodyAccMean
tBodyAccJerkMean
tBodyGyroMean
tBodyGyroJerkMean

mean: Mean value
std: Standard deviation

Transformations or work that performed to clean up the data:
#-------------------------------------------------------------------------------
# 1. Merges the training and the test sets to create one data set.

step 1: download zip file from website
step 2: unzip data
step 3: load data into R
step 4: merge train and test data

#-------------------------------------------------------------------------------
# 2. Extract only the measurements on the mean and standard deviation for each measurement. 

step 1: load feature name into R
step 2:  extract mean and standard deviation of each measurements

# 3. Uses descriptive activity names to name the activities in the data set

step 1: load activity data into R
step 2: replace 1 to 6 with activity names

#-------------------------------------------------------------------------------
# 4. Appropriately labels the data set with descriptive variable names.

#-------------------------------------------------------------------------------
# 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each acti
