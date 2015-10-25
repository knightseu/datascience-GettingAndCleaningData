# Overview
The script run_analysis.R executes the 5 steps described in the course project's description.

# Variables
* x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the according downloaded files.
* x_data, y_data and subject_data merge the previous datasets.
* features contains the correct names for the x_data dataset
* mean_and_std_features column names stored in.
* activities data from activity_labels.txt.
* all_data merges x_data, y_data and subject_data in a big dataset.
* averages_data contains the relevant averages after applying ddply()
