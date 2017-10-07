No other transformations than the ones done in the script has been 
made on the data. After download the folder contain the data files
and unzipp it, the merges many different files into one single dataset call merge.data.
as it has been stated in the exercise.

After that, we extract only the measurements on the mean and standard deviation for each measurement.
Then we use descriptive activity names to name the activities in the data set.
This is done by reading the labels from the activity_labels.txt file

The output (data_tidy.txt) represents the average of each variable for each activity and each subject. 
It is a table ; each variable represented by a column, and each activity / subject is represented by a row.
The columns names are slightly modified from the "features.txt" input file content:
all parenthesis are removed. The row names merge the subject and the activity.
For instance, the row "1_LAYING" describes the means of the subject 1 for the LAYING activity.