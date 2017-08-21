
Getting and Cleaning Data Week 4 assignment.

1. Downloaded and unzipped the data file into my working directory
2. Downloaded R source code into R working Directory
3. Executed R source code to generate a tidy data file.


Data Description
Variable in data x are sensor signals meaured with waist-mounted smartphones. Variable in data y shows the activity type the people performed.

Code Explained

Code combined training data and test data, partial vvariables were extracted to create another dataset with the averages of the activity types for all subjects.  The mean and standard deviation was calculated for the new generated dataset. Each row is average of the activity type for all subjects. 

Code based on instructions of assignment

Read training and test dataset into R environment.
Read variable names into R environment. 
Read subject index into R environment. 
Merged training and test sets to create one data set.
Command rbind was used to combine test and training sets. 
Use of grep command to get column indexes for variable names mean and std. 
Approtiately labels the data with descriptive variable names.  Gave the selected descriptive names to variable columns. 
Created a second, independent tidy data set with the average of each varible for each activiy and each subject. 
