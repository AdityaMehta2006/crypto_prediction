# crypto_prediction
Using Arima and LSTM to predict crypto prices
# 🚀 Crypto Price Forecasting (LSTM + ARIMA)

## 📌 Overview
This project builds a **time series forecasting model** using **LSTMs (Deep Learning)** and **ARIMA (Statistical Model)** to predict cryptocurrency prices.  
- 📈 Uses **Yahoo Finance API** for real-time & historical data  
- 🔥 Compares **ARIMA vs. LSTM** for better accuracy  
- 🎯 **Supports multiple assets** (Crypto, Stocks, Forex, Commodities)  

## 📂 Dataset
- **Source:** Yahoo Finance  
- **Default Asset:** `BTC-USD` (Bitcoin)  
- **Supports:** `ETH-USD`, `AAPL`, `EURUSD=X`, `GC=F` (Gold Futures), etc.  

## 🛠️ Installation & Setup
```bash
pip install yfinance pandas numpy matplotlib scikit-learn statsmodels tensorflow keras
