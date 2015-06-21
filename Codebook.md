#downloads required data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
1.Unzips the file if it has not been uncompressed
2.Creates results folder if it does not exist (all files are stored in this folder)
3. Loads features.txt used for columns,loads X_train.txt, y_train.txt, subject_train.txt, X_train contains the data using the feature data set as columns, y_train contains the activity labels, subject_train contains the ids
4. Loads and appends test dataset using X_test.txt, y_test.txt, subject_test.txt,X_test contains the data using the feature data set as columns,y_test contains the activity labels
subject_test contains the ids
5. Appends train and test data
6. Rearrange the data using id, loads activity_labels.txt, changes the data activity row to use the activity labels
7. Saves the mean and std into mean_and_std.csv
8. Saves the tidy dataset into tidy_dataset.csv
9. Mean_and_std.csv
contains 1 0300 (including header) rows and 82 columns (including enumeration column) in a default csv format

10. tidy_dataset.csv.csv
contains 181 rows (including header) and 82 columns (including enumeration column) in a default csv format



