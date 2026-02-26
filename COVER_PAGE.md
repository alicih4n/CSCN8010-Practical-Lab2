# COVER PAGE

---

**Student Name:** Ali Cihan Ozdemir

**Student ID:** 9091405

**Course:** CSCN8010 - Machine Learning Fundamentals

**Assignment:** Practical Lab 2: Multivariate Linear Regression, Non-Parametric Models and Cross-Validation

**GitHub Repository:** https://github.com/alicih4n/CSCN8010-Practical-Lab2.git

---

## Project Summary

This assignment involved building and evaluating various machine learning models using the Scikit-Learn Diabetes dataset to predict disease progression one year after baseline. The project was divided into three main parts:

**Part 1: Data Preparation & Exploratory Data Analysis (EDA)**
- Loaded the diabetes dataset (442 samples, 10 features)
- Performed comprehensive EDA with visualizations including scatter plots, histograms, and correlation heatmaps
- Split data into Training (75%), Validation (10%), and Test (15%) sets

**Part 2: Univariate Polynomial Regression**
- Built polynomial regression models (degrees 0-5) using only the BMI feature
- Compared models using R², MAE, and MAPE metrics
- Selected the best model based on validation performance
- Created visualizations showing the polynomial fit

**Part 3: Multivariate Modeling**
- Implemented 8 different models:
  - 2 Polynomial Regression models (with/without interaction terms)
  - 2 Decision Tree models (shallow vs deep)
  - 2 KNN Regressor models (k=3 and k=10)
  - 2 Logistic Regression models (binary classification with different regularization)
- Compared all models using appropriate metrics
- Provided academic justification for using classification metrics with Logistic Regression

**Key Results:**
- Univariate model achieved approximately 30-40% R² using BMI alone
- Multivariate models significantly improved performance to 40-50% R²
- Logistic Regression achieved approximately 70% accuracy on binary classification

---

**Date Submitted:** February 2026
