# Code book
This is the code book for tidy data set


# Variables Description

features - features.txt

activities - activity_labels.txt

subject_test - test/subject_test.txt 

x_test - test/X_test.txt

y_test - test/y_test.txt

subject_train - test/subject_train.txt 

x_train - test/X_train.txt

y_train - test/y_train.txt

X is created by merging x_train and x_test.

Y is created by merging y_train and y_test.

Subject is created by merging subject_train and subject_test.

Merged_Data is created by merging Subject, Y and X.

TidyData is created by subsetting Merged_Data.

FinalData is created by sumarizing TidyData.

Export FinalData into FinalData.txt file.
