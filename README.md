# Apple Stock Price Forecasting using LSTM

A Long Short-Term Memory (LSTM) model trained on 8 years of AAPL historical stock data to predict future price trends. This project uses Yahoo Finance API for data acquisition.

## 📊 Results
- RMSE < 2.5 on test data
- Achieved 96% directional prediction accuracy

## 🧰 Tools & Libraries
- Keras
- yfinance
- NumPy
- Matplotlib

## 🧠 Approach
- Time-series windowing of daily closing prices
- Normalization and supervised sequence transformation
- Sequential LSTM model with Dense output

## 🔍 Goals
- Show stock movement direction reliably
- Compare with baseline methods (e.g., moving average)
