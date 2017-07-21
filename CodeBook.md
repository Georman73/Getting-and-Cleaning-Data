Getting and Cleaning Data

Data Set Information:

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

Attribute Information:

For each record in the dataset it is provided: 
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.

Procedure:

1. Merges the training and the test sets to create one data set.

Read in data for source, combined the data, and assigned to variables of subject, test, and train

2. Extracts only the measurements on the mean and standard deviation for each measurement.

Extracted mean and standard deviation meansurements and combined it to the dataset 

3. Uses descriptive activity names to name the activities in the data set

Merged the Labels to the main dataset

4. Appropriately labels the data set with descriptive variable names.

Changed names as I saw appropriate

5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Data- Read into R:

features - Names of variables
Labels - Labels of Activity
subjectTrain - Subject Training Information
yTrain - Subject Training Information
xTrain - Training Data
subjectTest - Subject Test Information
yTest - Subject Test Information
xTest - Testing Data

Labels:

Activity
WALKIING
WALKING_UPSTAIRS
WALKING_DOWNSTAIRS
SITTING
STANDING
LAYING

Variables:

Angle(GravityMean)

Angle(tBodyAccelerationMean,Gravity

Angle(tBodyAccelerationmotionMean),GravityMean

Angle(tBodyGyromotionMean,GravityMean

Angle(tBodyGyromotionmotionMean,GravityMean

FrequencyBodyAccelerationMagnitudeMean

FrequencyBodyAccelerationMagnitudeMeanFreq

FrequencyBodyAccelerationMagnitudeSTD

FrequencyBodyAccelerationMean

FrequencyBodyAccelerationMeanFreq

FrequencyBodyAccelerationmotionMagnitudeMean

FrequencyBodyAccelerationmotionMagnitudeMeanFreq

FrequencyBodyAccelerationmotionMagnitudeSTD

FrequencyBodyAccelerationmotionMean

FrequencyBodyAccelerationmotionMeanFreq

FrequencyBodyAccelerationmotionSTD

FrequencyBodyAccelerationSTD

FrequencyBodyGyromotionMagnitudeMean

FrequencyBodyGyromotionMagnitudeMeanFreq

FrequencyBodyGyromotionMagnitudeSTD

FrequencyBodyGyromotionMean

FrequencyBodyGyromotionMeanFreq

FrequencyBodyGyromotionmotionMagnitudeMean

FrequencyBodyGyromotionmotionMagnitudeMeanFreq

FrequencyBodyGyromotionmotionMagnitudeSTD

FrequencyBodyGyromotionSTD

TimeBodyAccelerationMagnitudeMean

TimeBodyAccelerationMagnitudeSTD()

TimeBodyAccelerationMean

TimeBodyAccelerationmotionMagnitudeMean

TimeBodyAccelerationmotionMagnitudeSTD

TimeBodyAccelerationmotionMean

TimeBodyAccelerationmotionSTD

TimeBodyAccelerationSTD

TimeBodyGyromotionMagnitudeMean

TimeBodyGyromotionMagnitudeSTD

TimeBodyGyromotionMean

TimeBodyGyromotionmotionMagnitudeMean

TimeBodyGyromotionmotionMagnitudeSTD

TimeBodyGyromotionmotionMean

TimeBodyGyromotionmotionSTD

TimeBodyGyromotionSTD

TimeGravityAccelerationMagnitudeMean

TimeGravityAccelerationMagnitudeSTD

TimeGravityAccelerationMean

TimeGravityAccelerationSTD




