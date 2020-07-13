# Regression: Housing Dataset

#### Aim: Predict target variable ```SalePrice``` using suitable features.

Approach:
	* Load and inspect data.
	* Separate Numerical & Categorical Data in train dataset.
	* Check for Null Values in Numerical & Categorical Data
	* Impute missing values with suitable values in Numerical Data
	* Deal with outliers in Numerical Data having significant correlation with the target variable ```SalePrice```
	* Impute null values in Categorical Features.
	* Encode Ordinal and Nominal Features using a suitable encoding method.
	* Select Features using model based approach, here ```RandomForestRegressor``` is used to obtain importance of various features.
	* Fit and test a Regression Model using selected features.
	* Perform Hyperparameter Tuning to obtain best parameters.
	* Extract necessary features from Test Data.
	* Make predictions on test data and submit predictions.

