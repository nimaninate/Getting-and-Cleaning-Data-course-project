Getting and Cleaning Data Project

After setting the source directory for the files, read into tables the data located in
features.txt
activity_labels.txt
subject_train.txt
x_train.txt
y_train.txt
subject_test.txt
x_test.txt
y_test.txt
Assign column names and merge to create one data set.
Create a logcal vector that contains TRUE values for the ID, mean and stdev columns and FALSE values for the others. Subset this data to keep only the necessary columns.
Merge data subset with the activityType table to cinlude the descriptive activity names
Use gsub function for pattern replacement to clean up the data labels.
Per the project instructions, we need to produce only a data set with the average of each veriable for each activity and subject
