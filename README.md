# Predicting-House-Prices-Using-the-Boston-Housing-Dataset
# 🏠 Predicting House Prices Using the California Housing Dataset

This project builds and evaluates machine learning regression models to predict **median house prices** in California based on the **California Housing dataset**. It includes data preprocessing, model training, performance evaluation, and prediction from user input.

> ⚠️ **Note:** Though the original task refers to the *Boston Housing Dataset*, this implementation uses the *California Housing Dataset* (`housing.csv`).

---

## 📂 Project Structure

- `housing.csv` – California Housing dataset
- `README.md` – Project documentation

---

## 🧠 Objective

Build regression models **from scratch** (Linear Regression, Random Forest, XGBoost) to:

1. Predict house prices
2. Compare performance using RMSE and R²
3. Visualize feature importance
4. Enable user interaction for predictions

---

## 🔄 Workflow Overview

### 1. 📊 Data Preprocessing
- Missing values in `total_bedrooms` are filled with the **median**.
- The categorical column `ocean_proximity` is **one-hot encoded**.
- All **numerical features are normalized** using `StandardScaler`.

### 2. 🤖 Model Implementation
Currently uses built-in models (to be replaced with from-scratch implementations for full credit):

- `LinearRegression` from `sklearn`
- `RandomForestRegressor` from `sklearn`
- `XGBRegressor` from `xgboost`

### 3. 📈 Performance Evaluation
Models are evaluated using:
- **RMSE (Root Mean Squared Error)**
- **R² Score (Coefficient of Determination)**

### 4. 📌 Feature Importance
Feature importance plots are generated for:
- Random Forest
- XGBoost

---
