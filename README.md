# 🛒 RetailPulse — Advanced EDA & Feature Engineering Pipeline

Advanced EDA & feature engineering pipeline that transforms raw e-commerce order data into a clean, ML-ready dataset — statistical imputation, IQR/Z-score outlier treatment, and 7 engineered features.

## 📌 Overview

RetailPulse takes a raw, 1,200-row e-commerce order dataset and turns it into a mathematically clean, machine-learning-ready dataset. The pipeline handles missing data with both business-aware and statistical imputation methods, detects and neutralizes outliers, and engineers new predictive features — all built with Pandas, NumPy, SciPy, and Scikit-learn.

## 🎯 What This Project Covers

- **Missing Data Handling** — business-logic imputation for categorical gaps, plus a reusable Mean/Median/KNN imputation utility for numeric columns
- **Outlier Detection & Treatment** — IQR method (primary) cross-checked with Z-Score, outliers neutralized via winsorization (no rows dropped)
- **Feature Engineering** — 7 new predictive features spanning:
  - Temporal patterns (`Order_Month`, `Order_DayOfWeek`, `Is_Weekend`)
  - Unit economics (`Price_Per_Unit`)
  - Promotional behavior (`Has_Coupon`)
  - Customer loyalty signal (`Customer_Order_Count`)
  - Cart behavior (`Cart_Fill_Ratio`)

## 🛠️ Tech Stack

- Python
- Pandas & NumPy
- SciPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

## 📂 Project Structure
