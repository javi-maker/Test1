---
title: "CodeBook"
author: "Xavier Aguiar"
date: "6/8/2021"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Getting and Cleaning Data - Course Project

Processing
Creating a single data set by combining the training and test sets and extracting only the mean and standard deviation measures for each measurement.

To name the activities in the data collection, we used descriptive activity names.

Using descriptive variable names to appropriately label the data collection.

Making a separate tidy data set with the average of each variable for each activity and each subject.

Variables
features <- features.txt : 561 rows, 2 columns The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ.

activities <- activity_labels.txt : 6 rows, 2 columns List of activities performed when the corresponding measurements were taken and its codes (labels)

s_test <- test/s_test.txt : 2947 rows, 1 column contains test data of 9/30 volunteer test subjects being observed

x_test <- test/X_test.txt : 2947 rows, 561 columns contains recorded features test data

y_test <- test/y_test.txt : 2947 rows, 1 columns contains test data of activities’code labels

s_train <- test/subject_train.txt : 7352 rows, 1 column contains train data of 21/30 volunteer subjects being observed

x_train <- test/X_train.txt : 7352 rows, 561 columns contains recorded features train data

y_train <- test/y_train.txt : 7352 rows, 1 columns contains train data of activities’code labels

