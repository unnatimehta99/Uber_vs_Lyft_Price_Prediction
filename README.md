# Uber vs Lyft Price Prediction

## Introduction
Deciding between Uber and Lyft, the two major ride-hailing services in the U.S., involves navigating their subtle differences. Adaptive pricing, which fluctuates based on factors like location and time, adds complexity. To make an informed choice, comparing real-time prices on both apps is crucial. Understanding frequently used locations in Boston for pick-up and drop-off further enhances decision-making in this competitive landscape.

## Problem Definition
To interpret different conclusions such as:

* Temperature: Whether the number of rides increase with increase in temperature?
* Location: Is the price dependent on the source or destination? Are remote rides expensive?
* Cab Company: Which cab company gets more rides? Is it Uber or Lyft.
* Type of Cab: What is the first choice of the cab for long distances? It might be Uber XL for extra comfort and leg space.
* How many other factors depend on the fares of the cab?

## Data Overview
Dataset: https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma
The Boston Uber Lyft dataset covers the time period from November 2018 to December 2018, containing 693,072 data points with 56 variables. Among these, 10 are categorical, 46 are numerical, and there's one target variable: Price. The dataset provides details on pick-up and drop-off locations, ride dates and times, fare information, and the type of vehicle used.

## Classification Models
We explored several regression models to predict the price:
* Multiple Linear Regression
* Ridge Regression
* Lassso Regression
* Elastic Net Regression
* Polynomial Regression
* Random Forest Regressor
* XGBoost Regressor

## Feature Elimination
Correlation plot was used to eliminate features that have low correlation with target variable. Also, used Recursive Feature Elimination (RFE) to select features by recursively considering smaller and smaller sets of features. 

## Model Performance
We use the MAE, MSE, RMSE and R2Score 
  
## Conclusion
This project showcases the power of features in generating legal case summaries. By leveraging machine learning techniques, we successfully built accurate models for text summarization. 

