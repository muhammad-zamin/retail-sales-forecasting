
# 🛍️ Retail Sales Forecasting with Time Series (Internship Project)

This project was completed as part of a 25-day Data Science Internship. The goal was to build a time series forecasting model to predict monthly retail sales for the next 6 months, using mock historical data.

---

## 📌 Project Objective

Forecast monthly sales for a retail store to support:
- Inventory management
- Financial planning
- Marketing strategy

---

## 📊 Dataset

- **Type:** Mock retail sales data
- **Duration:** 4 years (Jan 2020 – Dec 2023)
- **Columns:** Date, SalesAmount, Promotion, HolidayMonth

---

## 🧱 Steps Completed

### 1. Exploratory Data Analysis (EDA)
- Time series visualization
- Decomposition (trend, seasonality, residual)
- ADF test for stationarity
- ACF/PACF plots

### 2. Feature Engineering
- Lag features (lag_1, lag_12)
- Rolling mean (3-month)
- Date parts (month, quarter)
- External features: Promotion, HolidayMonth

### 3. Model Building
- Used SARIMAX model: (1,1,1)(0,1,1,12)
- Trained on 42 months, validated on last 6
- Performance:
  - MAE: 814.37
  - RMSE: 1012.38

### 4. Forecasting
- Forecasted sales for Jan–Jun 2024
- Included exogenous variables
- Confidence intervals generated

---

## 🔮 Forecast Highlights

| Month | Forecast | 95% CI             |
|-------|----------|--------------------|
| Jan   | 15,387   | 13.7k – 17.0k       |
| Feb   | 18,653   | 16.7k – 20.6k       |
| Mar   | 14,954   | 12.8k – 17.1k       |
| Apr   | 13,468   | 11.1k – 15.8k       |
| May   | 11,059   | 8.5k – 13.6k        |
| Jun   | 10,514   | 7.8k – 13.2k        |

---

## 📌 Business Recommendations

- Stock up in Q1 and Q4 (sales peaks)
- Schedule promotions strategically in Feb, Dec
- Use forecast ranges to plan safe inventory buffers
- Explore external data (weather, economy) for future model improvement

---

## 📁 Files Included

- `sales_forecasting_step1_eda.ipynb` – Full notebook
- `sales_forecast_next_6_months.csv` – Final forecast data
- `Sales_Forecasting_Report_Summary.txt` – Project summary
- `Sales_Forecasting_Presentation.pptx` – Slide deck

---

## 🚀 Tools Used

- Python, Jupyter Notebook
- Pandas, Matplotlib, Statsmodels
- SARIMAX (Seasonal ARIMA)
- Anaconda environment

---

## 🧠 Author

**Name:** Muhammad Zamin  
**Internship:** 25-Day Data Science Internship  
**LinkedIn:** https://www.linkedin.com/in/muhammad-zamin-datascience-professional 
**GitHub:** https://github.com/muhammad-zamin

---

> ⭐ If you found this helpful, please star the repo!
