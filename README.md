# 🛒 Walmart Sales Forecasting

## 📌 Project Overview
Walmart is one of the world’s largest retail chains, operating multiple hypermarkets across regions.  
This project focuses on **analyzing and forecasting weekly sales data** for **45 Walmart stores**, with special emphasis on understanding the **impact of holidays on sales performance**.

The dataset includes historical weekly sales data along with key economic and seasonal indicators. The goal is to perform **exploratory data analysis (EDA)** and apply **time series forecasting techniques** to predict future sales trends.

---

## 🎯 Business Objectives
- Analyze historical weekly sales trends across Walmart stores  
- Study the impact of major holidays on store sales  
- Identify seasonality and patterns in sales data  
- Build predictive models to forecast future weekly sales  
- Support business decisions related to inventory planning and demand forecasting  

---

## 📂 Dataset Information
- **Source:** Kaggle  
- **Dataset:** Walmart Sales Forecast  
- **Link:** https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast  

### Key Features:
- Store ID  
- Weekly Sales  
- Holiday Flag  
- Temperature  
- Fuel Price  
- CPI (Consumer Price Index)  
- Unemployment Rate  
- Date  

---

## 🛠️ Tools & Technologies Used
- **Programming Language:** Python  
- **Libraries:**
  - Pandas, NumPy – Data manipulation
  - Matplotlib, Seaborn – Data visualization
  - Scikit-learn – Machine learning & evaluation
  - Statsmodels – Time series analysis
  - PMDARIMA – Auto ARIMA modeling
- **Techniques:**
  - Exploratory Data Analysis (EDA)
  - Feature Scaling
  - Time Series Decomposition
  - Forecasting Models

---

## 🔍 Methodology
1. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Converted date fields to datetime format
   - Scaled numerical features for model stability  

2. **Exploratory Data Analysis**
   - Sales trend visualization
   - Holiday vs non-holiday sales comparison
   - Seasonality and autocorrelation analysis  

3. **Time Series Analysis**
   - Stationarity testing using ADF test
   - Decomposition into trend, seasonality, and residuals  

4. **Model Building**
   - Linear Regression
   - Random Forest Regressor
   - ARIMA
   - Auto ARIMA
   - Exponential Smoothing (Holt-Winters)

5. **Model Evaluation**
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)

---

## 📈 Results & Insights
- Sales show clear **seasonal patterns**, especially during holiday weeks  
- **Holiday periods significantly impact weekly sales**, particularly Thanksgiving and Christmas  
- Time series models like **ARIMA and Exponential Smoothing** performed well for forecasting  
- Machine learning models helped capture non-linear relationships in sales drivers  

---

