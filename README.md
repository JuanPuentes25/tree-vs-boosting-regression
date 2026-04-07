# tree-vs-boosting-regression
Machine learning project to predict used car prices using regression models. Compares Linear Regression, Decision Trees, Random Forest, and Gradient Boosting (LightGBM) based on RMSE, training time, and inference speed.


# 🚗 Car Price Prediction ML

Machine learning project to predict the market value of used cars based on historical listings and vehicle characteristics.  

This project was developed as part of a practical study comparing different regression models, focusing on prediction quality, training time, and inference speed.

---

## 📌 Project Overview

Rusty Bargain, a used car marketplace, is developing an application that allows users to quickly estimate the market value of their vehicles.

The goal of this project is to build and evaluate machine learning models that can accurately predict car prices using structured data.

---

## 🎯 Objectives

- Predict car prices with high accuracy
- Compare multiple machine learning models
- Evaluate:
  - Prediction quality (RMSE)
  - Training time
  - Inference speed

---

## 📊 Dataset

The dataset contains historical listings of used cars, including:

- Vehicle specifications (brand, model, power, fuel type)
- Registration details (year, month)
- Usage (mileage)
- Metadata (date crawled, last seen, etc.)

**Target variable:**
- `Price` (in euros)

---

## 🧠 Models Used

The following models were implemented and compared:

- Linear Regression (baseline)
- Decision Tree Regressor
- Random Forest Regressor
- LightGBM Regressor
- (Optional) XGBoost / CatBoost

---

## ⚙️ Methodology

1. Data preprocessing:
   - Handling missing values
   - Encoding categorical features (OHE / native methods)
2. Feature engineering
3. Model training with hyperparameter tuning
4. Performance evaluation using RMSE
5. Comparison of:
   - Model accuracy
   - Training time
   - Prediction speed

---

## 📈 Evaluation Metric

The primary evaluation metric used is:

- **RMSE (Root Mean Squared Error)**

---

## ⏱️ Performance Comparison

| Model                        | RMSE (€) | Training Time (s) | Prediction Time (s) |
| ---------------------------- | -------- | ----------------- | ------------------- |
| Linear Regression            | 3360.89  | 1.5510            | 0.0975              |
| Decision Tree                | 2121.75  | 5.9241            | 0.0950              |
| Random Forest                | 2144.59  | 24.3259           | 0.1306              |
| Gradient Boosting (LightGBM) | 1764.51  | 4.6059            | 0.4440              |



---

## 🛠️ Tech Stack

- Python
- Pandas / NumPy
- Scikit-learn
- LightGBM
- (Optional) XGBoost / CatBoost
- Jupyter Notebook

---
