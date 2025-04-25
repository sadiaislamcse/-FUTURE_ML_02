# 📈 Stock Price Prediction Using Machine Learning

This project focuses on building and evaluating machine learning models to forecast stock prices based on historical data. It explores both traditional regression techniques and advanced deep learning models (LSTM) to perform time series prediction.

## 🔍 Project Overview

The goal is to develop a predictive model capable of forecasting future stock prices by learning from historical trends. The project involves:

- Data collection using Yahoo Finance API  
- Data preprocessing and feature scaling  
- Applying regression and LSTM models  
- Model evaluation using MAE, RMSE, and visualization of results  

## 🛠️ Tools & Technologies

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Keras, Matplotlib, yfinance

  ## 📊 Key Features

- Time series forecasting using LSTM (Long Short-Term Memory) networks  
- Visual comparison of actual vs. predicted stock prices  
- Performance evaluation using standard regression metrics  
- Modular and clean code structure for reproducibility

  ## 📊 Results

🌲 **Random Forest Regressor** successfully captured short-term dependencies in the stock price using lag features, offering a robust non-linear forecasting model.

📉 **Mean Squared Error (MSE):** ~11.23  
📈 **Mean Absolute Error (MAE):** ~2.34  
🔍 **R² Score:** ~0.97  
*(Values may vary slightly depending on dataset split and random seed)*

📊 Visualizations of predicted vs. actual prices on the test set showed close alignment, confirming the model’s ability to follow recent trends.

📆 Creating lag-based features for the previous 7 days significantly improved the model’s ability to understand short-term trends.

💡 This project emphasized the importance of **feature engineering** (like lagging), and how **ensemble models** like Random Forests can perform well even without deep learning.

