# Getting and Cleaning Data

## Course Project

The Course Project involves creating an R script called run_analysis.R that does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps by Step Process Involved for this Course Project are as follows: 

1. Download the data source (rar file) into a working directory (parent folder) on your local drive. 
2. Extract the data source rar file into a new folder named ```UCI HAR Dataset```. This folder is inside the working directory (parent folder) .
3. Put ```run_analysis.R``` inside the working directory (parent folder of ```UCI HAR Dataset```) 
4. Then open RStudio, using ```setwd()``` function in RStudio, set parent folder (chosen by us initially) as your working directory.
5. Run ```source("run_analysis.R")```, then it will generate a new file ```tidy_data.txt``` in your working directory.

## Dependencies

```run_analysis.R``` file will help you to install the dependencies automatically. It depends on ```reshape2``` and ```data.table```. 
