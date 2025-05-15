# Diabetes Prediction using Machine Learning

This project predicts whether a person has diabetes based on diagnostic measurements. It uses machine learning models trained on the Pima Indians Diabetes Dataset.

## 🔍 Problem Statement

Diabetes is a common health concern, and early prediction can help in timely medical intervention. The goal is to create a predictive model that can classify individuals as diabetic or not based on several medical parameters.

## 💡 Project Objective

To develop a machine learning model that predicts the likelihood of diabetes using historical patient data.

## 📁 Dataset Used

- **Name:** Pima Indians Diabetes Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features:**
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (0 or 1)

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas, NumPy, Matplotlib, Seaborn
- XGBoost
- SMOTE (for class imbalance handling)

## ⚙️ Algorithms Used

- Logistic Regression
- Random Forest
- XGBoost (final model with best accuracy)

## 📈 Model Accuracy

Achieved up to **75% accuracy** using XGBoost with SMOTE oversampling.

