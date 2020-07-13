# Regression: Housing Dataset

#### Aim: Predict target variable ```SalePrice``` using suitable features.

Approach:
1. Load and inspect data.
2. Separate Numerical & Categorical Data in train dataset.
3. Check for Null Values in Numerical & Categorical Data
4. Impute missing values with suitable values in Numerical Data
5. Deal with outliers in Numerical Data having significant correlation with the target variable ```SalePrice```
6. Impute null values in Categorical Features.
7. Encode Ordinal and Nominal Features using a suitable encoding method.
8. Select Features using model based approach, here ```RandomForestRegressor``` is used to obtain importance of various features.
9. Fit and test a Regression Model using selected features.
10. Perform Hyperparameter Tuning to obtain best parameters.
11. Extract necessary features from Test Data.
12. Make predictions on test data and submit predictions.

