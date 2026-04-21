# 📈 CONCOR Stock Price Forecast using ARIMA

## 📌 Problem Statement
The objective of this project is to analyze historical stock price data of CONCOR (Container Corporation of India) and build a predictive time series model using ARIMA. The goal is to identify patterns in stock price movements and forecast future prices.

---

## 🎯 Objective
- Analyze historical stock price data of CONCOR  
- Check stationarity using ADF test  
- Apply ARIMA model for forecasting  
- Predict stock prices for the next 30 days  

---

## 📊 Dataset
- **Source:** Yahoo Finance  
- **Stock:** CONCOR (NSE)  
- **Duration:** Last 1 year (daily data)  
- **Features:**
  - Date  
  - Open  
  - High  
  - Low  
  - Close  
  - Volume  
- **Size:** ~250 trading days  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Converted date column into datetime format  
- Checked and handled missing values  

### 2. Exploratory Data Analysis (EDA)
- Visualized closing price trends  
- Observed fluctuations and volatility in stock prices  

### 3. Model Building
- Performed Augmented Dickey-Fuller (ADF) test for stationarity  
- Applied first-order differencing to make data stationary  
- Used ACF & PACF plots to determine ARIMA parameters (p, d, q)  
- Built ARIMA model for time series forecasting  

### 4. Evaluation
- Compared predicted values with actual values  
- Forecasted stock prices for the next 30 days  

---

## 📈 Results & Observations
- The closing price trend shows moderate fluctuations over the past year  
- The stock does not follow a perfectly stable trend and exhibits volatility  
- ADF test indicated that the original data was non-stationary  
- After first-order differencing, the data became stationary  
- ARIMA model successfully captured the overall movement of stock prices  

### 🔮 Forecast Insight
- Slight fluctuations are expected in the next 30 days  
- Mild upward tendency observed  
- No strong continuous upward or downward trend  

---

## ⚠️ Limitations
- Stock market volatility is not fully captured  
- External factors like news, economic conditions, and policies are not considered  

---

## 🤖 AI Ethics & Responsible Usage
This project was completed with AI assistance for guidance. All execution, implementation, and validation were performed independently.

---

## 🚀 How to Run
pip install -r requirements.txt
python main.py

---
## 📌 Conclusion

The ARIMA model effectively analyzed and forecasted CONCOR stock prices. The results suggest that the stock is expected to remain relatively stable in the short term with minor fluctuations. However, predictions should be interpreted cautiously due to market uncertainties.

---
## 👨‍🎓 Student Details
- Name: Huzaifa Saiyad
- Roll No: 48
- UIN: 231A041
- -Year: TE-AIDS
- Course: Engineering (Artificial Intelligence & Data Science)
