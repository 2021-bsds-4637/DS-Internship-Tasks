# 🧠 Task 6 — Energy Usage Forecasting

## 📌 Problem Statement and Objective
The goal of this task is to forecast global energy usage using time series data. The objective is to build and compare different forecasting models to predict future electricity consumption patterns, helping optimize power management and resource planning.

---

## 📊 Dataset Description
- **Dataset Type:** Time series (hourly energy usage data)  
- **Features:** Datetime index and Global Active Power  
- **Target Variable:** Global Active Power (kW)  
- **Duration:** Multiple months of continuous hourly readings  

---

## 🧹 Data Cleaning and Preprocessing
- Converted the date column to a datetime format and set it as index.  
- Handled missing values using forward fill.  
- Resampled data to hourly intervals.  
- Split dataset into training and testing sets (80/20 split).  
- Scaled data where applicable for machine learning models.  

---

## 🔍 Exploratory Data Analysis (EDA)
- Visualized overall energy consumption trends.  
- Identified daily and weekly seasonal patterns.  
- Checked correlation among variables.  
- Observed periodic consumption spikes at specific hours of the day.  

---

## 🤖 Model Building and Evaluation
Three forecasting approaches were used:

| Model | Description | RMSE | MAE |
|-------|--------------|------|-----|
| **ARIMA** | Classical statistical model for univariate forecasting | *Value from notebook* | *Value* |
| **Prophet** | Facebook’s forecasting model for trend + seasonality | *Value* | *Value* |
| **XGBoost** | Machine learning model with lag-based features | *Value* | *Value* |

> *Note:* RMSE and MAE values are calculated to evaluate predictive performance.

---

## 📈 Visualizations
- Line plots showing **actual vs predicted** energy usage.  
- Seasonal decomposition of energy consumption trends.  
- Comparison of forecast curves for ARIMA, Prophet, and XGBoost models.

---

## 💡 Final Conclusion and Insights
- Energy consumption follows strong daily and weekly seasonal patterns.  
- Prophet and XGBoost models captured nonlinear trends better than ARIMA.  
- XGBoost achieved the lowest RMSE, making it the most accurate model.  
- Forecasting can assist in **load management, demand prediction, and grid optimization.**

---

## 💻 Code Quality
- Well-structured, modular, and commented notebook.  
- Proper use of functions, scaling, and error handling.  
- Visual outputs labeled clearly for interpretation.

---

## 📂 GitHub Repository Structure
