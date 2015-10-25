# Overview
The script run_analysis.R executes the 5 steps described in the course project's description.

# Variables
* __x_train__, __y_train__, __x_test__, __y_test__, __subject_train__ and __subject_test__ contain the data from the according downloaded files.
* __x_data__, __y_data__ and __subject_data__ merge the previous datasets.
* __features__ contains the correct names for the __x_data__ dataset.
* __activities__ contains data from activity_labels.txt.
* __mean_and_std_features__ contains column name.
* __all_data__ merges __x_data__, __y_data__ and __subject_data__.
* __averages_data__ contains the relevant averages after applying __ddply()__
