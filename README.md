California Housing Price Prediction using Linear Regression 
In this project, we aim to predict housing prices in California using a linear regression model and improve the results using the XGBoost regression technique.

Data Preprocessing
We start with importing the data from a CSV file and cleaning it by removing any missing values. We then perform feature scaling using the StandardScaler from sklearn.preprocessing to ensure all features are on the same scale.

We also perform data visualization to understand the relationships between different features and the target variable. This helps in identifying any outliers and selecting the relevant features for our model.

Finally, we split the data into training and testing sets using train_test_split from sklearn.model_selection to evaluate our model's performance on unseen data.

Linear Regression Model
We create a linear regression model using LinearRegression from sklearn.linear_model and fit the training data to it. We then use the model to make predictions on the testing data and evaluate its performance using the mean absolute error (MAE) and R-squared (R2) metrics.

XGBoost Regression
We then use XGBoost regression to boost the performance of our linear regression model. We create an XGBRegressor model from xgboost and fit it to the training data. We then use this model to make predictions on the testing data and evaluate its performance using MAE and R2 metrics.

Results
Our linear regression model achieved an MAE of 50397.38168031163 and R2 of 0.65 on the testing data. After boosting the model using XGBoost regression, the MAE improved to 32508.97375443479 and R2 improved to 0.82.

These results indicate that XGBoost regression was successful in improving the performance of our linear regression model.

Conclusion
In conclusion, we were able to predict housing prices in California using a linear regression model and improve its performance using XGBoost regression. The project demonstrates the importance of data preprocessing and model evaluation using appropriate metrics.
