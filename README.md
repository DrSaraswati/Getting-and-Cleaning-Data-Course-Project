# Getting-and-Cleaning-Data-Course-Project
Getting and Cleaning Data Course Project

## Introduction
This repository contains my solution to project of the Coursera course "Getting and Cleaning Data", part of the  Data Science specialization.

The dataset is at [UCI HAR Dataset](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)


##Analysis Script
run_analysis.R will do the following tasks and prerequisites: 

Tasks: 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set named **avg_data.txt** with the average of each variable for each activity and each subject in the  **"UCI HAR Dataset"** directory.

Prerequisites:

1. UCI HAR Dataset must been extracted as a directory **"UCI HAR Dataset"** in the R working directory.

##Code Book
The CodeBook.md file explains the transformations performed and the resulting data and variables
