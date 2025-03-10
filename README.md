# Intellihack_DataDominators_TaskNumber4


##Financial Stock Price Prediction

Project Overview

This repository contains a comprehensive analysis of financial time series data, including exploratory data analysis (EDA), data preprocessing, model training, evaluation, and prediction. The project aims to analyze historical financial data and develop predictive models to forecast future price movements.
Table of Contents


Data Description
Exploratory Data Analysis
Data Preprocessing
Model Training and Selection
Results and Evaluation
File Structure
Installation and Usage
Future Improvements


Data Description
The dataset contains historical financial time series data with the following features:


Date
Open price
High price
Low price
Close price
Trading volume
Adjusted close price
Additional derived features


Exploratory Data Analysis
The EDA process involved:

Initial data loading and inspection
Analysis of data distribution and temporal patterns
Identification of trends, seasonality, and anomalies
Feature correlation analysis
Visualization of key patterns and relationships

Key findings from the EDA:

Data quality issues in older historical records
Clear cyclical patterns and trends in price movements
Significant correlation between trading volume and price volatility

Data Preprocessing
Data preprocessing steps included:

Removal of unwanted columns
Temporal filtering to focus on the most recent 20 years
Handling of missing values by dropping null entries
Verification of zero volume records
Checking and removal of duplicate entries
Feature engineering for model input

Model Training and Selection
Multiple modeling approaches were tested and evaluated:

Linear Regression
Random Forest
XGBoost
Decision Tree
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
ARIMA (AutoRegressive Integrated Moving Average)
SARIMA (Seasonal ARIMA)
LSTM (Long Short-Term Memory neural network)
RNN (Recurrent Neural Network)

Models were evaluated using:

R² Score (Coefficient of Determination)
Root Mean Squared Error (RMSE)
Visual comparison of predicted vs. actual values

Results and Evaluation
After thorough evaluation, Linear Regression emerged as the best-performing model, showing:

Highest R² score and lowest RMSE
Consistent predictions across different market conditions
Good alignment between predicted and actual values
