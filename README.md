# age-group-classification-ml-hackathon
Classify age group (Adult vs Senior) using ML models and health data — includes SVM, XGBoost, GridSearchCV, and F1-based evaluation.
# Age Group Classification - ML Hackathon 🧠🎯

This project classifies individuals as **Adult (age < 65)** or **Senior (age ≥ 65)** using demographic and health features. It was developed as part of a Machine Learning hackathon challenge.

---

## 📁 Dataset

The data is derived from a preprocessed version of NHANES. It includes the following features:

- `RIAGENDR`: Gender (1 = Male, 2 = Female)
- `PAQ605`: Weekly exercise activity
- `BMXBMI`: Body Mass Index
- `LBXGLU`: Glucose level
- `DIQ010`: Diabetes status
- `LBXGLT`: Glucose tolerance
- `LBXIN`: Insulin level  
- `age_group`: **Target** (0 = Adult, 1 = Senior)

---

## 📊 Problem Statement

Predict whether a person belongs to the **Adult (0)** or **Senior (1)** age group based on the above features.

---

## ✅ ML Models Tried

- Logistic Regression (L1 & L2)
- SVM 
- Random Forest
- XGBoost
- LightGBM
- Decision Tree
- KNN
- Gaussian Naive Bayes

---

## 🛠 Techniques Used

- Data Cleaning & Imputation
- Exploratory Data Analysis (EDA)
- Feature Scaling (StandardScaler)
- Class Imbalance Handling (`class_weight='balanced'`)
- Hyperparameter Tuning (GridSearchCV)
- Evaluation Metrics: F1 Score, Confusion Matrix, ROC Curve


