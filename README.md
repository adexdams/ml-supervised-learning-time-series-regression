# ML Supervised Learning Time Series Regression
I executed a Kaggle competition "Blue Book for Bulldozers" to predict the auction sale price for heavy equipment.

* This demo was developed following the completion of the "Complete A.I. & Machine Learning, Data Science Bootcamp" courses: https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/


## Problem Statement
The instruction from Kaggle was to predict the sale price of a particular piece of heavy equipment at auction based on its usage, equipment type, and configuration.


## Data
**Source of data:** The data is sourced from auction result postings and includes information on usage and equipment configurations.
* Kaggle - https://www.kaggle.com/c/bluebook-for-bulldozers/data


## What you should expect
The following steps were taken on the dataset to develop an ML model:
First, there are two notebooks in this presentation, 03 Supervised learning, ends with an overfitting problem in the model score. In contrast, 04 Supervised learning ended with a resolution to the overfitting problem and correction of the model.
Then the usual steps were taken on both documents:
1.	Data exploration was carried out to gain clarity on the extent of the data.
2.	The missing datasets were replaced with median data and data types were changed to categorical data types.
3.	The data was split by the time series (SaleYear) to group into training and validation datasets.
4.	The classification ML model deployed was a Logistic Regression and scored on MAE and RMSLE
5.	A function was used to process the data and make the model work on new datasets.
6.	It also showed a hyperparameter tunning that used RandomizedSearchCV to find the best parameters and ultimately resulted in model improvement.
7.	Finally, it concluded with a function that ranked the features by importance.



## Next Steps
See the Python notebook attached to this repository for the modeling work.

