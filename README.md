# Getting and Cleaning Data Course Project

Description of  how run_analysis.R script works.
* The first step is to  unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
* Make sure the folder "data" and the run_analysis.R script are both in the current working directory.
* Secondly, use source("run_analysis.R") command in RStudio. 
* Third step will let you  find two output files are generated in the current working directory:
  - merged_data.txt which contains a data frame called cleanedData .  data_with_means.txt which  contains a data frame called result.
* Final and the last step where you use data <- read.table("data_with_means.txt") command in RStudio to read the file. 
