Question: 1) a tidy data set as described below, 2) a link to a Github
repository with your script for performing the analysis, and 3) a code
book that describes the variables, the data, and any transformations or
work that you performed to clean up the data called CodeBook.md. You
should also include a README.md in the repo with your scripts. This repo
explains how all of the scripts work and how they are connected.

Work flow: 
1) Download zip file, load training and test data. 
2) Load
dplyr library 
3) Read training (X,Y, subject) and test (X,Y, subject)
data into corresponding tables 
4) Row bind training data to test data 
5) Replace the numeric values in Y to activity names
6) Select mean and std
functions
7) Rename functions to a readable format
8) Separate dataset for grouped mean
