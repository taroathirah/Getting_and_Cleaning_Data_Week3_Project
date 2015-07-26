# Getting_and_Cleaning_Data_Week3_Project
Coursera Module 3 Assignment 3

Data Sources

Here are the data used for this course project https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Related Files

1. README.md - Course Project Description
2. CodeBook.md - Variables, data and transformation did with data sources in order to produce the result
3. run_analysis.R - Complete R code

Goals

Provided run_analysis.R code does the following: 1. Merges the training and the test sets to create one data set. 2. Extracts only the measurements on the mean and standard deviation for each measurement. 3. Uses descriptive activity names to name the activities in the data set. 4. Appropriately labels the data set with descriptive variable names. 5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

In order to run run_analysis without error, place this script into Data source folder "UCI HAR Dataset" and set this folder as your working directory.

Steps Explaination for run_analysis.R

Step 1
Read all related data sources from test and train folder
Merge those data as one data source

Step 2
Read features file while retains its mean and standard deviations values

Step 3
Read activity labels
Update labels name with activity labels

Step 4
Standardize column names and tidy up the presentation

Step 5
Find means for each combinations of subjects and labels
This dataset is distributed AS-IS and no responsibility implied or explicit can be addressed to the authors or their institutions for its use or misuse. Any commercial use is prohibited.

Jorge L. Reyes-Ortiz, Alessandro Ghio, Luca Oneto, Davide Anguita. November 2012.
