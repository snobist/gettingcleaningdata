gettingcleaningdata
===================

#Purpose

To undertake the course project for Getting and Cleaning Data course on Coursera

#Goal

Per the course project instructions, conduct the full process of reading, loading the Samsung sensor data set and all the ensuing measures necessary for generating a tidy data set. It is mean to demonstrate the student’s knowledge of the whole process of tidying data set

#Key steps

Read and load the Samsung data set and the reshape2 package for R required for carrying out melt and cast functions;
Create one R script called run_analysis.R;
Merges the training and the test sets to create one data set;
Extracts only the mean and standard deviation measurement out of the original data set. 
Uses descriptive activity names to name the activities in the data set.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

#Instructions
Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.
Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.
