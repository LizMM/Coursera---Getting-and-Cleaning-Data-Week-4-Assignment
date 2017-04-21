# Coursera---Getting-and-Cleaning-Data-Week-4-Assignment
Submissions for the Week 4 Assignment of the Getting and Cleaning Course

This repository contains my submitted files for the Week 4 Assignment for the Coursera Getting and Cleaning Data Course and contains the following files:

### R Script: run_analysis.R

The prerequistites for running this script are the working directory has already been set.

Executing the run_analysis.R script completes the following:
- Downloads and unzips the source data files into the set working directory.
- Creates vectors containing the features and activity label information which are used to add descriptors later in the script. 
- Reads into seperate tables the training set, the associated activity IDs and  subject IDs.
- Reads into seperate tables the test set, the associated activity IDs and subject IDs.
- Merges the training and the test sets to create one data set.
- Merges the activity ID and subject ID tables for the training and test sets.  
- Labels the merged dataset with descriptive variable names using the created 'features' vector.
- Ads in 2 columns to the merged dataset so an activity ID and subject ID are assigned to each row.
- Extracts only the measurements on the mean and standard deviation for each measurement. The measurements have been selected where suffixed with mean() or std() which are the mean and standard deivation measurements for the signals.  
- Uses descriptive activity names to name the activities in the data set and ensures the dataset columns are ordered correctly with the subject ID and activity description in the first two columns.
- Creates tidy data set called 'TidyData' which contains the average of each variable for each activity and each subject.  The data set is ordered by subject ID. 
- Creates a text file of 'TidyData' so it can be uploaded.  

## CodeBook.md

A code book that describes the variables, the data, and transformations used to tidy the data.

## TidyData

A text file containing the tidied data set.  In order to view the data in R please use the following script: 
