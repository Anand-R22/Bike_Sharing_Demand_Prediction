# 🚴‍♂️ Bike Sharing Demand Prediction — End-to-End ML Project

This repository demonstrates a complete **end-to-end machine learning workflow** for predicting hourly bike rental demand using historical usage data. The project walks through the **entire lifecycle of a data science project** — from raw data exploration to model training and evaluation — following **clean, reproducible, and modular practices** suitable for both academic projects and professional portfolios.

The dataset includes features such as:

- **Timestamp** (date and hour)
- **Season**  
- **Weather conditions**  
- **Holiday / working-day flags**  
- **Temperature, humidity, windspeed**

These features are **engineered and leveraged** to train supervised regression models that estimate total rentals per hour.

---

## 🔎 Key Sections

### 1. Data Preprocessing
- Checking for missing values  
- Data type conversions  
- Timestamp decomposition (hour, day, month, season)  
- Treatment of skewed distributions  

### 2. Exploratory Data Visualization
- Visualizing trends across **seasons** and **weather patterns**  
- Analyzing **working days vs holidays**  
- Identifying **peak and off-peak hours**  

### 3. Feature Engineering & Preparation
- Creating **numerical, categorical, and cyclic time features**  
- Applying **one-hot encoding**  
- Train-test splitting for model evaluation  

### 4. Model Building & Evaluation
- Training **baseline linear regression** and **tree-based regressors**  
- Benchmarking using **RMSE, MAE, and R²**  
- Selecting models for interpretability and predictive power  

---

## 🎯 Goal
To develop an **interpretable ML model** that accurately predicts bike demand, helping operators:

- Optimize fleet allocation  
- Reduce shortages  
- Handle peak-time logistics proactively  

---

> Built with **Python**, **pandas**, **scikit-learn**, **matplotlib**, **seaborn**, and **Jupyter Notebook**.
