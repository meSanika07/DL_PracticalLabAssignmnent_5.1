# 📊 Experiment 5.1 - Univariate Time Series Forecasting using LSTM

## 🎯 Objective
To forecast future values of a univariate time series using LSTM-based deep learning models.

---

## 📚 Dataset Used
- **TCS Stock Prices** (from Yahoo Finance using `yfinance`)
- Duration: `2010-01-01` to current date

---

## 🔧 Tools and Libraries

```python
pandas, numpy, matplotlib, seaborn  
tensorflow (Keras), scikit-learn  
yfinance
```

## 🧪 Experiment Steps

1. **Import Required Libraries**

2. **Fetch Historical Stock Data using `yfinance`**

3. **Data Preprocessing**
   - Dropping unnecessary columns
   - Scaling using `MinMaxScaler`
   - Creating sequences for LSTM (100 time steps)

4. **Data Visualization**
   - Plotting stock closing prices
   - 100-day and 200-day Moving Averages

5. **Train-Test Split**
   - 70% Training, 30% Testing

6. **Model Building**
   - 4 LSTM layers with Dropouts
   - Dense output layer

7. **Model Training**
   - Optimizer: Adam
   - Loss: Mean Squared Error
   - Metric: Mean Absolute Error

8. **Predictions and Visualization**
   - Plotting Predicted vs Actual values
   - ![Predicted vs Actual Prices](![image](https://github.com/user-attachments/assets/b2176707-4cec-47c1-b3e2-618bc7b5f6d1)

9. **Model Evaluation**
   - RMSE (Root Mean Squared Error)
   - MAE (Mean Absolute Error)

---

## 📎 Suggested Alternative Datasets

- Daily Minimum Temperatures – Melbourne  
- COVID-19 Daily Cases – Our World in Data  
- Airline Passengers Dataset  
- Electricity Consumption Dataset  
- Weather Data – Seattle or London  
- Sunspot Activity Dataset  
- Energy Usage – PJM Hourly Energy Consumption  
- Bitcoin Price Time Series  
- Retail Sales Forecasting – Walmart Dataset  

---
## 🙌 Acknowledgements

- Yahoo Finance for real-time stock data  
- TensorFlow/Keras for deep learning framework
