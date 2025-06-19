# Stock-Price-Prediction
**📈 Stock Price Prediction**
This project implements a comprehensive workflow to forecast stock closing prices using two approaches: Moving Average (baseline) and LSTM (deep learning). It’s designed for educational purposes and to serve as a strong foundational model for real-world applications.

**🔍 Overview**
The notebook guides you through:
Acquiring historical stock price data (e.g., via yfinance)
Exploratory Data Analysis and plotting price trends
Implementing a simple moving average algorithm
Preprocessing for and enabling LSTM time-series forecasting
Performance comparison and visual inspection of predictions

**📈 Dataset & Data Fetching**
Uses stock symbol inputs (e.g., AAPL, MSFT)
Fetches historical Open, High, Low, Close, and Volume values via yfinance
Data is split into train/test sets, scaled, reshaped, and formatted for LSTM

**🧭 Notebook Workflow**
Import packages & set up API for data downloads
Fetch historical price data
Plot closing prices to understand trends
Implement moving average model as baseline
Prepare data for LSTM: scaling, windowing, and train-test split
Build and train the LSTM model
Generate predictions on train/test sets
Visualize and compare training & testing predictions against actual prices

**🤖 Modeling Approaches**
**1. Moving Average**
Uses a sliding average (e.g., 10-period) to forecast next point
Simple to implement and serves as a comparative baseline
**2. LSTM (Long Short-Term Memory)**
A deep learning model tailored for sequence prediction
Handles time-series data using sliding window input
Implemented with multiple layers and dropout regularization

**📊 Results & Evaluation**
Visual comparison of moving average vs. real price
Overlay of LSTM train/test predictions on original price
Qualitative assessment of model performance
(Optional) Metrics like RMSE can be added for quantitative evaluation
