# 📈 USD/INR Exchange Rate Prediction

## 📝 Overview
This project analyzes the **USD/INR exchange rate** using **Linear Regression** to predict closing prices based on **Open, High, Low, and Close (OHLC) values**. The study compares the predictive accuracy of models trained on **historical data** versus **OHLC data**, evaluating their effectiveness in forecasting market trends.

## 📊 Dataset
- **Source**: USD/INR exchange rate dataset  
- **Period**: December 2003 – August 2023  
- **Columns**: 4,567 (daily OHLC values)  

## 🛠️ Methodology
1. **Data Preprocessing**: Cleaned and structured **20 years** of financial data.  
2. **Model Training**: Applied **Linear Regression** to predict closing prices.  
3. **Error Analysis**: Measured model performance using **Mean Squared Error (MSE)**.  
4. **Comparative Study**: Evaluated models based on:
   - Historical data alone  
   - OHLC-based data  

## 🔍 Results
- Predicted close value for **November 3, 2023**:
  - **Historical Data Model**: ₹81.065  
  - **OHLC Data Model**: ₹83.258  
- Actual close value: ₹83.1745  
- Achieved **MSE of 0.017**, demonstrating the effectiveness of using OHLC data for improved predictions.

## 📌 Key Insights
- Models using **OHLC features** showed superior accuracy compared to historical data alone.  
- Understanding **Bull and Bear trends** is crucial for predicting financial market movements.  
- Incorporating additional technical indicators may further enhance predictive accuracy.

## 🚀 Technologies Used
- **Python** (pandas, NumPy, scikit-learn, Matplotlib)  
- **Machine Learning** (Linear Regression)  
- **Financial Data Analysis**  

## 🏆 Future Enhancements
- Implementing **LSTM and other time-series models** for improved accuracy.  
- Exploring **additional economic indicators** for robust forecasting.  
- Developing a **real-time prediction dashboard** for live currency tracking.  
