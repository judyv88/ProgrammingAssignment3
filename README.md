# ProgrammingAssignment3


Instructions for project

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.

One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

You should create one R script called run_analysis.R that does the following.

    Merges the training and the test sets to create one data set.
    Extracts only the measurements on the mean and standard deviation for each measurement.
    Uses descriptive activity names to name the activities in the data set
    Appropriately labels the data set with descriptive variable names.
    From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Get the Data
1.Download the file and put the file in the data folder
2.Unzip the file
3.Unzipped files are now in the folderUCI HAR Dataset and get the list from this dataset

Read data from the targeted files
1. Read data from the files into the variables
2. Look at the properties of the above varibles

Merge the training and the test sets to create one dataset
1. Merge the data tables by rows
2. Set names to variables
3. Merge columns to get the data frame Data for all data

Extract only the mean and standard deviation for each measurement
1. Subset Name of Features by measurements on the mean and standard deviation
2. Subset the data frame Data by seleted names of Features
3. Check the structures of the data frame Data

Use descriptive activity names to name the activities in the dataset
1. Read descriptive activity names from “activity_labels.txt”
2. Factorize Variable activity in the data frame Data using descriptive activity names

Appropriately label the dataset with descriptive variable names

Create a tidy data set 
Produce Codebook

