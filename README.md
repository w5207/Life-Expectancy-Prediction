# Life-Expectancy-Prediction
By Ning Chen and Yuqian Ran

This is a group project of Stat 441(University of Waterloo). 

We used the provided data to build a model predicting whether people would be satisfied with their life.

The data contains 271 varibles, ids and satisfied(the data used 0/1 to represent whether this person is satisfied with his/her life).

1. We did the data preprocessing. We transformed the object data to float and filled the missing values using RandomForest.
2. We built LightGBM, RandomForest, and XGBoost models and selected the model with best performance. 
