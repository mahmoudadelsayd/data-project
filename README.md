#Getting-and-Cleaning-Data-Project

Question1:Please upload the tidy data set created in step 5 of the instructions. Please upload your data set as a txt file created with write.table() using row.name=FALSE (do not cut and paste a dataset directly into the text box, as this may cause errors saving your submission).


Question2: 
Please submit a link to a Github repo with the code for performing your analysis. The code should have a file run_analysis.R in the main directory that can be run as long as the Samsung data is in your working directory. The output should be the tidy data set you submitted for part 1. You should include a README.md in the repo describing how the script works and the code book describing the variables.

Code Book
From Overview: A code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md.

README
I have included a README.md in the repo with my scripts. This repo explains how all of the scripts work and how they are connected.

#For 1st tiny data set:
Read data sets and combine them
Read subjects and combine them
Read data labels and combine them
Read features list
Subset only only std and mean features from list
Perform same subset on data set
Rename features to be more human readable
Read activity list
Rename activities to be more human readable
Rename data labels with activity name
Merge data, subjects, and labels to single tiny data set
Write tiny data set to file
#For 2nd tiny data set: average of measurement for activity and subject
Prepare empty data set of appropriate length for
Loop through subjects, then subloop through activities
For each activity in a subject, get the full list of measurements
Calculate the mean of each of these activities
Place the means in subsequent columns of the subject/activity row
Write second tiny data set to file

