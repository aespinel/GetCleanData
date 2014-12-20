GetCleanData
============

Coursera DataScience Assignment week 3 Clean and Getting Data

Introduction

This repository contains my course project for the Coursera "Getting and Cleaning data" course, as part of the Data Science specialization. 

About data

The features (variables - 561 of them) are unlabeled and can be found in the x_text. The activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file. The same structure is follwed by the training set.
the UCI HAR Dataset must be extracted and the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"

The script and the tidy dataset

The script run_analysis.R has the following steps:

1. Merge the test and training sets together. 
2. Labels are added and only columns that have to do with mean and standard deviation are kept.
3. Lastly, the script creates a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called tidy1.txt, which can also be found in this repository. I used the option row.names = FALSE as suggested by the instructor.

About the Code Book

The CodeBook.md file explains the transformations performed and the resulting data and variables.
