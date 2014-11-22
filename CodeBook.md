Code book:

>> Approach and design

This script processes disparate data files related to a the UCI Har project into one tidy dataset and then summarizes all the mean and standard deviation variables to generate one final output tidy dataset.  The resulting tidy dataset was then filtered to only return the variables that were mean or standard measurements.  This list is below:

"tBodyAccMeanX","tBodyAccMeanY","tBodyAccMeanZ","tBodyAccStdX","tBodyAccStdY","tBodyAccStdZ","tGravityAccMeanX","tGravityAccMeanY","tGravityAccMeanZ","tGravityAccStdX","tGravityAccStdY","tGravityAccStdZ","tBodyAccJerkMeanX","tBodyAccJerkMeanY","tBodyAccJerkMeanZ","tBodyAccJerkStdX","tBodyAccJerkStdY","tBodyAccJerkStdZ","tBodyGyroMeanX","tBodyGyroMeanY","tBodyGyroMeanZ","tBodyGyroStdX","tBodyGyroStdY","tBodyGyroStdZ","tBodyGyroJerkMeanX","tBodyGyroJerkMeanY","tBodyGyroJerkMeanZ","tBodyGyroJerkStdX","tBodyGyroJerkStdY","tBodyGyroJerkStdZ","tBodyAccMagMean","tBodyAccMagStd","tGravityAccMagMean","tGravityAccMagStd","tBodyAccJerkMagMean","tBodyAccJerkMagStd","tBodyGyroMagMean","tBodyGyroMagStd","tBodyGyroJerkMagMean","tBodyGyroJerkMagStd","fBodyAccMeanX","fBodyAccMeanY","fBodyAccMeanZ","fBodyAccStdX","fBodyAccStdY","fBodyAccStdZ","fBodyAccJerkMeanX","fBodyAccJerkMeanY","fBodyAccJerkMeanZ","fBodyAccJerkStdX","fBodyAccJerkStdY","fBodyAccJerkStdZ","fBodyGyroMeanX","fBodyGyroMeanY","fBodyGyroMeanZ","fBodyGyroStdX","fBodyGyroStdY","fBodyGyroStdZ","fBodyAccMagMean","fBodyAccMagStd","fBodyBodyAccJerkMagMean","fBodyBodyAccJerkMagStd","fBodyBodyGyroMagMean","fBodyBodyGyroMagStd","fBodyBodyGyroJerkMagMean","fBodyBodyGyroJerkMagStd","angle_tBodyAccMean_gravity","angle_tBodyAccJerkMean_gravityMean","angle_tBodyGyroMean_gravityMean","angle_tBodyGyroJerkMean_gravityMean","angle_X_gravityMean","angle_Y_gravityMean","angle_Z_gravityMean", "Subject", "ActivityId", "ActivityName"

These measurements were then summarized across all the subjects per each activity.


>> Variables information for the file GroupBySubjectActivityMeanVariables.txt


"Subject"
	Data Type: integer 
	Purpose: Representing the subject that the measurements are about
	Unit: Unitless
"ActivityName": 
	Data Type: String
	Purpose: To describe what the subject was doing during the study
	Unit: Unitless
"Variable"
	Data Type: String
	Purpose: To describe what is being observed and recorded as a measure
	Unit: Variable depending on the measurement
"MeanValue"
	Data Type: float
	Purpose: To hold the mean of all the measurements for the subject/activity pair
	Unit: Variable depending on the measurement
