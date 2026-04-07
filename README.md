# 📈 Advanced Multi-Horizon Stock Forecasting System (NIFTY50)

## 📌 Overview
This project presents a comprehensive stock forecasting system for NIFTY50 companies using a combination of classical time series models and advanced deep learning architectures. The goal is to improve prediction accuracy and evaluate real-world trading performance through backtesting.

---

## 🎯 Objectives
- Forecast stock prices for multiple future horizons (7-day, 30-day)
- Compare traditional time series models with deep learning approaches
- Improve prediction accuracy using ensemble techniques
- Evaluate real-world performance using backtesting strategies

---

## 🧠 Models Implemented

### 🔹 Classical Models
- ARIMA  
- SARIMA  
- Facebook Prophet  

### 🔹 Deep Learning Models
- LSTM (Long Short-Term Memory)  
- CNN-LSTM Hybrid  
- Transformer-based Model  

### 🔹 Ensemble Model
- Combined predictions from multiple models to improve accuracy and stability  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Historical NIFTY50 stock data (OHLCV)
- Data cleaning and normalization
- Feature scaling (MinMaxScaler)

---

### 2. Feature Engineering
- Technical indicators using `ta` library  
- Rolling statistics and trend indicators  
- Sequence generation for deep learning models  

---

### 3. Custom Loss Function 🔥
A hybrid loss function was designed to improve prediction quality:

- Price Loss (MSE)
- Directional Accuracy Loss
- Return-based Loss

---

### 4. Multi-Horizon Forecasting
- Short-term: 7-day predictions  
- Medium-term: 30-day predictions  

---

### 5. Model Evaluation Metrics
- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  
- R² Score  
- Directional Accuracy  

---

### 6. Backtesting Strategy 💰
- Simulated trading based on model predictions  
- Included transaction costs  
- Evaluated profitability and risk  

---

## 📊 Key Results

- Deep learning models outperformed traditional models in capturing complex patterns  
- Transformer-based model showed strong performance in multi-horizon forecasting  
- Ensemble model improved overall stability and accuracy  
- Backtesting demonstrated potential for profitable trading strategies  

---

## 📉 Visualizations
(Add your images in `/images` folder)

- Actual vs Predicted Prices  
- Model comparison charts  
- Backtesting profit curves  
- Heatmaps and performance metrics  

---

## 📂 Project Structure

cd nifty50-stock-forecasting
pip install -r requirements.txt
jupyter notebook
