# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2 - Ames Housing Data and Kaggle Challenge

Benjamin Toh, DSIF2


**Problem Statement**

To prevent company from losing customer to their competitors and to retain valuable customers


**Executive Summary**

The number of e-commerce companies has increased over the years. A problem that companies faced is that they are losing their customer to their competitors due to various reasons. This is also known as customer churning. Studies on customers' demographic and their browsing behaviors can help to analysis how companies can retain certain group of customers. Customer retention is impose lesser cost as compared to acquiring new customer due to the high marketing cost.  

This project will be ultilizing a e-commerce dataset which belongs to a Machine Learning Challenge hosted at Hacker Earth. It has 25 columns of different features relating to demographic, browsing behavior and transaction data. Exploration, cleaning, features engineering and modelling will be done using this data, to acheive the best model in predicting the churn risk score, ranging from 1 to 5 with 1 being the least and 5 being the most.

The objective is to create the best model by evaluation of F1 score and undergo deployment for companies to input their data and have an accurate prediction on the customer churn rsk score. 


**Conclusions and Recommendations**

Decision Tree Classifier and MixMaxScaler with cross validation the best model model for this multiclass classification. For a better modeling score, future works includes, using other classification algorithms like XGBoost or even neutrel network, etc to test if whether other models are better. More datas will be require for better prediction and more feature engineering will be done to improve the score.

In conclusion, models are not overfitted and the imbalance dataset are timely dealt with, by using parameters in the models such as 'One Vs Rest (ovr)' and 'balanced class weights'. A deeper exploration will also be done to have a deeper understanding on customer behaviors and to further on to Customer Lifetime value prediction. 


**Data**

Data sources: 

https://www.kaggle.com/parv619/hackerearth-how-not-to-lose-a-customer-in-10-days
