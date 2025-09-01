# ✈️ Time Series Forecasting – Air Passengers Data

## 📌 Project Overview  
This project focuses on **time series forecasting** using the classic **AirPassengers dataset**, which contains monthly totals of international airline passengers (1949–1960). The aim is to analyze patterns (trend, seasonality) and predict future passenger traffic.

---

## 🔍 Key Steps  
- 📂 **Data Loading & Exploration**: Read and explored the dataset.  
- 📊 **Visualization**: Plotted the time series to observe overall trends.  
- ✅ **Stationarity Check**: Performed **ADF test** and differencing.  
- 🔗 **ACF & PACF Analysis**: Identified significant lags for modeling.  
- 🤖 **Modeling**: Applied **Autoregression (AR)** model to forecast passenger counts.  
- 📈 **Evaluation**: Compared predicted values with test data.  

---

## 📊 Results  
- The dataset showed a **clear upward trend** with **seasonal fluctuations**.  
- Forecast captured both **growth trend** and **seasonality**.  

![Forecast Plot](results/forecast_plot.png)

---

## 🧰 Tech Stack  
- **Python**: Pandas, NumPy, Matplotlib  
- **Statsmodels**: ADF test, Autoregression, ACF, PACF  

---

## ▶️ How to Run  
Clone the repo and install dependencies:
```bash
git clone https://github.com/YourUsername/Time_Series_DataScience.git
cd Time_Series_DataScience
pip install -r requirements.txt
