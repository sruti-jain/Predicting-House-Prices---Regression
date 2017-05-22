## Predicting-House-Prices---Regression

This project aims to determine the housing prices of California properties for new sellers and also for buyers to estimate the profitability of the deal. 

I have used the data taken from California census data with 20,640 instances in the dataset and the shows a summary of the numerical attributes is as shown below:

![alt text](https://github.com/sruti-jain/Predicting-House-Prices---Regression/blob/master/images/DatasetSummary.PNG)

The dataset was split into Train-Validate-Test samples using Stratified sampling. Various exploratory analysis was done to determine which features was useful and which could be eliminated. Upon finalization of the features, text features were converted to categorical variables and feature standarization was performed to implicitly weights all features equally in their representation.

Next in order to select a prediction method, various regression methods were explored and compared. The performance measure used to compare various prediction models was RMSE (Root mean square error). Grid Search and Randomized Search was also implemented to determine the hyperparameters for Random forest that will give the least prediction error. Below are the details of the models implemented and their performance score:

1. Linear Regression:        RMSE- 68321.7051304
2. Decision Tree Regressor:  RMSE- 70269.5738668
3. Random Forest Regressor:  RMSE- 52909.1080535
4. Support Vector Regressor: RMSE- 110914.791356
5. Fine Tuning the Hyperparameters for Random Forest Regressor: RMSE- 49261.2835608

