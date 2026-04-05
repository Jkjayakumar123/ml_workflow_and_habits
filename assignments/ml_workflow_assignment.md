# ML Workflow Assignment

## 📌 Problem Overview
You are given a retail dataset and asked to predict whether a customer will make a repeat purchase within 30 days.

---

## ✅ Task 1 — Label and Data Leakage

### 🎯 Label Column
**repeat_purchase_flag**  
This is the target variable because it indicates whether a customer made a repeat purchase within 30 days, which is the outcome we want to predict.

---

### ⚠️ Data Leakage Column
**discount_used_on_repeat_order**  
This column introduces data leakage because it contains information about the repeat purchase event itself, which would not be available at the time of prediction.

---

## ✅ Task 2 — Missing ML Workflow Steps

### 🔍 1. Exploratory Data Analysis (EDA)
Before training a model, it is important to understand the dataset by analyzing distributions, identifying outliers, and checking relationships between variables. This helps in selecting relevant features and avoiding incorrect assumptions.

---

### ⚙️ 2. Data Preprocessing & Feature Engineering
Handling missing values, scaling numerical features, and creating meaningful features are critical steps to ensure the data is clean and suitable for modeling, which directly impacts model performance.

---

## 🚀 Final Summary
- Identified the correct target variable  
- Detected a feature causing data leakage  
- Highlighted key ML workflow steps before modeling  
