# Gettting-data-course-project
This repository consists the code file for the week 4 project of the "Getting and Cleaning Data" course.
The dataset corresponds to an experiment performed with 30 volunteers across different age groups who perform various actvities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) 
with a smartphone tied to their waist which records the various parameters.
The dataset is divided into two parts : testing and training data.

For the assesment we have to combine the testing and training dataset and extract selected variables to create another meaningful, consise dataset.
The new dataset contains variables calculated based on mean and standard deviation.
Each row is gives the average for each variable for all activities.

The R script, run_analysis.R does the following:
1. Merges the trainig and testing datasets.
2. Extracts only mean and standard deviation measurements for each measurement.
3. Use descriptive names for activity names and features
4. Creates an independent clean dataset with averages of each variable for each activity and subject
