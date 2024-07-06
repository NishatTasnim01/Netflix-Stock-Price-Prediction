<h1 align="center"> Netflix Stock Price Prediction </h2>

This repository contains code for predicting Netflix (NFLX) stock prices using two different machine learning models: Long Short-Term Memory (LSTM) for time series forecasting and Logistic Regression.

## Overview
The project aims to forecast the closing stock prices of Netflix using historical data. Two models are implemented and compared:

- **LSTM Model**: Utilizes deep learning techniques for time series prediction.
- **Logistic Regression Model**: A classical machine learning approach adapted for stock price prediction.

## Dataset
The dataset used is NFLX.csv containing daily stock prices from Kaggle.

## Data Exploration and Preprocessing
- The dataset is loaded and initial exploratory analysis is performed to understand its structure and check for null values.
- The 'Close' column is selected as the target variable for prediction.
- Data normalization is performed using MinMaxScaler to scale the data between 0 and 1.
- LSTM requires data to be reshaped into a format suitable for time series forecasting.

## Evaluation Metrics
Both models are evaluated using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score to assess their performance in predicting stock prices.

## Usage
To run the models:
- **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/netflix-stock-price-prediction.git

- **Install the required dependencies:**
   ```bash
   pip install tensorflow scikit-learn pandas matplotlib

## Contribute
🚀 Contributions are welcome! Please fork the repository and create a pull request with your improvements.

