# Human Activity Recognition Using Smartphones Dataset

tidydata.txt contains the final tidy data set.
 
CodeBook.md explains the dataset contained in the tidydata.txt

run_analysis.R has the R script used to generate the tidydata set from the original data.

The script reads the test data and train data. Selects the meana and sd columns fom the dataset. It then adds the subject and activity columns to these data frames. Then it row combines both of them to get the total data. Then it uses the melt from and cast from reshape2 package to average all the columns in the original data for each subject and activity.

   
