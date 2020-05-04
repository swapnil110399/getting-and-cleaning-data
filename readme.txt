Getting and Cleaning Data Project John Hopkins Coursera

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.



Load Packages and get the Data




Load activity labels + features




 Load train datasets


Load test datasets


merge datasets and add labels



 Convert classLabels to activityName basically. More explicit