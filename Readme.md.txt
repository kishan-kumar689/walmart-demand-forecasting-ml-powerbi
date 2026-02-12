# 🏬 Walmart Demand Forecasting & Supply Chain Optimization  
### (Machine Learning + Power BI Analytics Project)

---

## 📌 Project Overview

This project builds an end-to-end **Retail Demand Forecasting System** using:

- 📊 Machine Learning (Python)
- 📈 Power BI Executive Dashboards
- 📦 Supply Chain Error Analysis

The objective is to forecast Walmart weekly sales at Store-Department level and evaluate forecast performance using enterprise KPIs such as:

- RMSE
- MAE
- wMAPE
- Forecast Accuracy %
- Forecast Bias

---

## 🧠 Machine Learning Pipeline

### 1️⃣ Data Engineering
- Lag feature creation (lag_1, lag_2)
- Date feature extraction (Year, Month, Week)
- One-hot encoding for Store Type
- Holiday indicators
- CPI, Fuel Price, Unemployment features

### 2️⃣ Model Training
- Model Used: Gradient Boosting Regressor
- Validation Strategy: Time-based split
- Features used:


Feature schema saved in: `models/feature_cols.json`


### 3️⃣ Model Artifacts
- Trained model saved as: `models/model_gbr.pkl`
- Feature schema: `models/feature_cols.json`

---

## 📊 Power BI Dashboard

Three Professional Dashboards Built:

### 🔹 1. Forecast Performance
- Actual vs Predicted Sales
- Forecast Accuracy %
- RMSE Trend
- Forecast Bias
- Top 10 Stores by Error

### 🔹 2. Business Sales Insights
- Monthly Sales Trend
- Sales Variance
- Store Performance Ranking
- Department Performance

### 🔹 3. Store & Type Analysis
- Sales by Store Type
- Revenue Mix
- Size vs Sales Analysis
- Store-Dept Error Heatmap

---

## 📈 Business Impact

✔ Identify high-error stores  
✔ Detect over/under forecasting bias  
✔ Improve inventory planning  
✔ Enable supply chain optimization  
✔ Executive-level KPI monitoring  

---

## 🛠 Tech Stack

- Python (Pandas, NumPy, Scikit-learn)
- Gradient Boosting Regression
- Feature Engineering
- Power BI (Advanced DAX)
- GitHub Version Control

---

## 📁 Repository Structure

### 3️⃣ Model Artifacts
- Trained model saved as: `models/model_gbr.pkl`
- Feature schema: `models/feature_cols.json`

---

## 📊 Power BI Dashboard

Three Professional Dashboards Built:

### 🔹 1. Forecast Performance
- Actual vs Predicted Sales
- Forecast Accuracy %
- RMSE Trend
- Forecast Bias
- Top 10 Stores by Error

### 🔹 2. Business Sales Insights
- Monthly Sales Trend
- Sales Variance
- Store Performance Ranking
- Department Performance

### 🔹 3. Store & Type Analysis
- Sales by Store Type
- Revenue Mix
- Size vs Sales Analysis
- Store-Dept Error Heatmap

---

## 📈 Business Impact

✔ Identify high-error stores  
✔ Detect over/under forecasting bias  
✔ Improve inventory planning  
✔ Enable supply chain optimization  
✔ Executive-level KPI monitoring  

---

## 🛠 Tech Stack

- Python (Pandas, NumPy, Scikit-learn)
- Gradient Boosting Regression
- Feature Engineering
- Power BI (Advanced DAX)
- GitHub Version Control

---

## 📁 Repository Structure

Data/
Notebooks/
models/
PowerBI/
PowerBI_Screenshots/


---

## 🚀 Future Improvements

- XGBoost / LightGBM implementation
- Hyperparameter tuning
- Cross-validation
- Model deployment using Streamlit
- Real-time dashboard integration

---

## 👨‍💻 Author

Built as a complete ML + BI retail forecasting solution.

