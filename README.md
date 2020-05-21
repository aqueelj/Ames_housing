# Ames_housing
Predicting the housing prices in Ames Iowa using advanced regression techniques: 
This problem is part of a kaggle competition.

Data:
The dataset contains features of houses in Ames such as Lot frontage, Pool, Fireplace, etc. with Sale Price as the output variable.

Code:
The following operations have been performed in the code
a) The null values have been replaced by the mean in the numeric columns. For non numeric values , the null values have been replaced by the category with the highest frequency.

b)Next the appropriate features have been picked out using Recursive Feature Elimination (RFECV) for Linear regression.

c) After applying Linear regression, we get an RMSE of 0.18715

d)Next we follow the same steps to apply Random Forest regressor. This gives us an RMSE of around 0.16

e) Finally we use XGBoost because its performance capability and ability to handle null values. This gives us an RMSE of 0.13010
