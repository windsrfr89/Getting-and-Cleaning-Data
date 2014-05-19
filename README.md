## Getting and Cleaning Data - Course Project

### Purpose
The run_analysis function was designed to combine, summarize, and make clean a  
set of data collected from the embedded accelerometer and gyroscopes of Samsung  
Galaxy S smartphones.

The original data was collected as part of a study designed to explore the  
possibility of human activity recognition using smartphones. A full description  
is available at the site where the original data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

### Relevant Files

* 'README.md'
 * You're reading it!

* 'getdata-projectfiles-UCI HAR Dataset.zip'
 * This is the un-altered data from the original study linked above that  
 r_analysis will work it's magic on.
 * **It should be un-zipped and the UCI HAR Dataset directory placed inside your  
 working directory before running r_analysis.R**
 * It can be downloaded here:  
 https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
 
* 'run_analysis.R'  
 * R script that contains the r_analysis function, which takes the original data  
 set as input and outputs the summarized, tidy data set as a "TidyData.txt" file  
 in your home directory.
 
* 'TidyData.txt'
 * Text file that is produced by running r_analysis() at the R programming prompt
 * Contains the averages per subject per activity of all the mean and standard  
 deviation variables from the original dataset
 
* 'CodeBook.md'
 * Description of the variables and how the run_analysis function works