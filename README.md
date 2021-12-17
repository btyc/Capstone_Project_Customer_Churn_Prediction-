# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2 - Ames Housing Data and Kaggle Challenge

Benjamin Toh, DSIF2


**Problem Statement**

How to prevent company from losing customer to their competitors and to retain valuable customers


**Executive Summary**

The number of e-commerce companies has increased over the years. A problem that companies faced is that they are losing their customer to their competitors due to various reasons. This is also known as customer churning. Studies on customers' demographic and their browsing behaviors can help to analysis how companies can retain certain group of customers. 

This project will be ultilizing a e-commerce dataset which belongs to a Machine Learning Challenge hosted at Hacker Earth. It has 25 columns of different features relating to demographic, browsing behavior and transaction data. Exploration, cleaning, features engineering and modelling will be done using this data, to acheive the best model in predicting the churn risk score, ranging from 1 to 5 with 1 being the least and 5 being the most.

During the exploration process, outliers were observed for features with mid to high correlations with sale price as well as missing values for some of the features. Cleaning of the data were done to remove the outliers and filled in the missing values. To further improve the model performmance, datas were selected and transform into features that better represent to predict sale price. Linear, Ridge and Lasso regressions together with scaling, train test split, cross validations were used in the modeling stage. The evaluation will be judged based on Root Mean Square Error (RMSE).


**Conclusions and Recommendations**

After modeling and Kaggle Challenge, Lasso regression using MixMaxScaler with cross validation is deemed to the be best model. However, there seems to be more outliers within the dataset alhough the distribution of the residuals are normally distributed but there a few large differences between actual and predicted sale price. The prototype model which 10 best features has a much higher root mean squared errors and is deem to be underfitting due to the simplicity of the model and the non-linearity between the actual and predicted sale price. 

After modeling and Kaggle Challenge, Lasso regression using MixMaxScaler with cross validation is deemed to the be best model. However, there seems to be more outliers within the dataset alhough the distribution of the residuals are normally distributed but there a few large differences between actual and predicted sale price. The prototype model which 10 best features has a much higher root mean squared errors and is deem to be underfitting due to the simplicity of the model and the non-linearity between the actual and predicted sale price.

For a better and more accurate prediction for the sale price, users on our app will be recommended to key in more feature details other than just the 10 basic features. 

In conclusion, further modeling will be carry out to minimise the underfitting problem and root mean squared error (RMSE). A deeper exploration will be needed on the dataset and enhanced feature engineering will be perform.  


**Data**

Data sources: 

https://www.kaggle.com/parv619/hackerearth-how-not-to-lose-a-customer-in-10-days

Data Dictionary


