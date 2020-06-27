# Getting-and-cleaning-data-Assignment

About the Data
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The run_analysis.R Script
run_analysis script takes the data mencioned above and does the following:
-Download and unzip source data if it doesn't exist.
Read the data and merge the training and the test sets to create one data set.
Extract only the measurements on the mean and standard deviation for each measurement.
Label the data set with descriptive variable names.
Create a n independent tidy set with the average of each variable for each activity and each subject.
Write the data set to the finaltidydata.txt file.
