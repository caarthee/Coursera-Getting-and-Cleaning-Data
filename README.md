# Coursera-Getting-and-Cleaning-Data

One of the most exciting areas in all of data science right now is wearable computing - see for example this article. Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users.
In this project, data collected from the accelerometer and gyroscope of the Samsung Galaxy S smartphone was retrieved, worked with, and cleaned, to prepare a tidy data that can be used for later analysis.
This repository contains the following files:
	• README.md, this file, which provides an overview of the data set and how it was created.
	• tidy_data.txt, which contains the data set.
	• CodeBook.md, the code book, which describes the contents of the data set (data, variables and transformations used to generate the data).
	• Run_analysis.R, the R script that was used to create the data set 





Creating the data set


The R script Run_analysis.R can be used to create the data set. It retrieves the source data set and transforms it to produce the final data set by implementing the following steps (see the Code book for details, as well as the comments in the script itself):
	• Download and unzip source data if it doesn't exist.
	• Read data.
	• Merge the training and the test sets to create one data set.
	• Extract only the measurements on the mean and standard deviation for each measurement.
	• Use descriptive activity names to name the activities in the data set.
	• Appropriately label the data set with descriptive variable names.
	• Create a second, independent tidy set with the average of each variable for each activity and each subject.
	• Write the data set to the tidy_data.txt file.
The tidy_data.txt in this repository was created by running the Run_analysis.R script using R version 3.5.2 (2018-12-20) on Windows 8.1 64-bit edition.
This script requires the dplyr package (version 0.8.0.1 was used).
