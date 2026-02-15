# 🍎 Apple Stock Price Prediction & Forecasting

An end-to-end Time Series analysis and forecasting project that predicts **Apple Inc. (AAPL)** stock prices using a variety of statistical and machine learning models. 

## 🚀 Overview
This project explores the historical stock data of Apple, performs stationarity tests, and implements multiple forecasting architectures to compare their performance in predicting future prices.

## 🛠️ Tech Stack
* **Data Source:** Yahoo Finance (`yfinance`)
* **Analysis:** Pandas, NumPy, Scipy
* **Visualization:** Matplotlib, Seaborn
* **Models:**
    * **Statistical:** ARIMA, GARCH
    * **Machine Learning:** XGBoost (with Optuna tuning)
    * **Time Series Specific:** Facebook Prophet
    * **Deep Learning:** Bidirectional LSTM (Long Short-Term Memory)

## 📊 Key Features
* **Exploratory Data Analysis (EDA):** Seasonal decomposition, ACF/PACF plots, and rolling statistics.
* **Stationarity Testing:** Augmented Dickey-Fuller (ADF) test.
* **Hyperparameter Optimization:** Used **Optuna** to find the best parameters for XGBoost.
* **Comparative Analysis:** Evaluation of models using **RMSE** (Root Mean Squared Error).

## 📈 Model Performance
The project compares different models to find the most accurate predictor for AAPL stock.
| Model | RMSE |
| :--- | :--- |
| LSTM | [9.76] |
| XGBoost | [10.61] |
| Prophet | [26.08] |
| Sliding Window | [30.45] |
| Rolling window | [57.85] |


