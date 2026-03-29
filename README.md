# 🩺 Diabetes Prediction with Ensemble Models

Predicting diabetes outcomes using machine learning ensemble methods 
on the Pima Indians Diabetes Dataset.

## 📊 Project Overview
Compared three classification models to predict diabetes diagnosis:
- **Random Forest** — 77.6% accuracy
- **XGBoost (default)** — 76.04% accuracy  
- **XGBoost (tuned with GridSearchCV)** — 77.6% accuracy ✅ Best Model

> Data cleaning improved model accuracy by replacing invalid zero values in medical columns (Glucose, BloodPressure, SkinThickness, Insulin, BMI) with median values.

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat)

## 📁 Dataset
- **Source:** Pima Indians Diabetes Database
- **Features:** Pregnancies, Glucose, Blood Pressure, BMI, Age, and more
- **Target:** Diabetes diagnosis (0 = No, 1 = Yes)

## 🔑 Key Features
- Glucose and BMI were the top predictors
- GridSearchCV hyperparameter tuning improved accuracy by ~2%

## 👤 Author
**Ayman Tabidi** — [LinkedIn](https://www.linkedin.com/in/ayman-tabidi-3575a53a0/) 
| [GitHub](https://github.com/aetabid)
