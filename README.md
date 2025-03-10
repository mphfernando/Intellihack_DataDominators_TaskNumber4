# Intellihack_DataDominators_TaskNumber4

# Financial Time Series Analysis and Prediction

## Project Overview

This repository contains a comprehensive analysis of financial time series data, including exploratory data analysis (EDA), data preprocessing, model training, evaluation, and prediction. The project aims to analyze historical financial data and develop predictive models to forecast future price movements.

## Table of Contents

1. [Data Description](#data-description)
2. [Exploratory Data Analysis](#exploratory-data-analysis)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Training and Selection](#model-training-and-selection)
5. [Results and Evaluation](#results-and-evaluation)
6. [File Structure](#file-structure)
7. [Installation and Usage](#installation-and-usage)
8. [Future Improvements](#future-improvements)

## Data Description

The dataset contains historical financial time series data with the following features:
- Date
- Open price
- High price
- Low price
- Close price
- Trading volume
- Adjusted close price
- Additional derived features

## Exploratory Data Analysis

The EDA process involved:
- Initial data loading and inspection
- Analysis of data distribution and temporal patterns
- Identification of trends, seasonality, and anomalies
- Feature correlation analysis
- Visualization of key patterns and relationships

Key findings from the EDA:
- Data quality issues in older historical records
- Clear cyclical patterns and trends in price movements
- Significant correlation between trading volume and price volatility

## Data Preprocessing

Data preprocessing steps included:
- Removal of unwanted columns
- Temporal filtering to focus on the most recent 20 years
- Handling of missing values by dropping null entries
- Verification of zero volume records
- Checking and removal of duplicate entries
- Feature engineering for model input

## Model Training and Selection

Multiple modeling approaches were tested and evaluated:
- Linear Regression
- Random Forest
- XGBoost
- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- ARIMA (AutoRegressive Integrated Moving Average)
- SARIMA (Seasonal ARIMA)
- LSTM (Long Short-Term Memory neural network)
- RNN (Recurrent Neural Network)

Models were evaluated using:
- R² Score (Coefficient of Determination)
- Root Mean Squared Error (RMSE)
- Visual comparison of predicted vs. actual values

## Results and Evaluation

After thorough evaluation, Linear Regression emerged as the best-performing model, showing:
- Highest R² score and lowest RMSE
- Consistent predictions across different market conditions
- Good alignment between predicted and actual values



## Installation and Usage

### Prerequisites

- Python 3.8+
- Required packages listed in requirements.txt

### Setup

1. Clone the repository:
   ```
   git clone https://github.com/username/financial-time-series-analysis.git
   cd financial-time-series-analysis
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

### Running the Analysis

1. Execute the notebooks in sequence:
   ```
   jupyter notebook notebooks/01_data_exploration.ipynb
   ```

2. Or run the complete pipeline:
   ```
   python src/main.py
   ```


