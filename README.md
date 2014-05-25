Getting-and-cleaning-data
=========================

The project and associated documentation for the getting and cleaning data course


The attached R markdown file should be downloaded and run in R to produce the Tidy dataset for this project.
The working directory should be set to the folder containing all the data for the project before the script is run.

An Overview of the scripts behavoiur is as follows.

* Import the features list and convert the variable names to "Camel" type naming convention
* Import the training and test sets and combine them together
* Using Grepl extract all the variables related to the mean and standard deviation
* Create a data frame of the means of each variable split by activity type and subject.
* Export the tidy data set as a text file using comma's as delimters

