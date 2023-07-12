# Retail_Sales_Prediction

I am going to analyse the Rossman Dataset and sales and making pridiction to improve the bussiness goal.

![image](https://github.com/akpatel94/Retail_Sales_Prediction/assets/49813219/0b678360-9106-479c-868b-4e78edf55cd7)


# Project Description : 

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.
You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

![image](https://github.com/akpatel94/Retail_Sales_Prediction/assets/49813219/f0d9ebcb-5a82-4d0b-a221-1ba2a7e297e2)

# Data Description
This dataset was originally used in a Kaggle competition The dataset contains information about the stores and its sales. Two datasets are provided.

stores_data.csv - historical data including Sales
store.csv - supplemental information about the stores

# 📖 Approach
there are some approches of dataset :

Loading our dataset and importing all the useful libraries
Data preprocessing and Feature Engineering
Scaling numeric features to a (0,1) range
Exploratory Data Analysis
Merging of Datasets
Encoding of categorical columns as one hot vectors
Feature Selection
Standardization of features
Machine Learning Data Modeling (for our Prediction)

# Algorithms Used:
Linear Regression
Cross Validation and Random Forest
XGBoost
decision Tree

# Conculusion:
Out of the four methods, Random Forest proved to be the most accurate, achieving a R2_Score of 0.984006, MAE of 293.127736 and RMSE of 488.157335. While it has the lowest error of all methods, it requires more work than the other three approaches and hence, comsumes more time to produce results.

From results, we can see that most important feature on which sale of store depends is 'Customers'. Also, the customer feature seems to depend on other features like Competition distance, Store type , Promo etc.

So, now we can say that the Rossmann store person can now implement the Random Forest Model and utilise the feature importance data for predicting the sales for next six months.
