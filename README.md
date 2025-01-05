## Loan-Approval-Prediction-Project
### Project Overview
This project aims to predict loan approval decisions based on applicant details using machine learning models. The pipeline includes data preprocessing, exploratory data analysis, hypothesis testing, feature engineering, and model training.

### Table of Contents
Introduction
Dataset
Project Steps
Key Features
Results

### Introduction
Loan approval is a critical decision-making process for financial institutions. This project leverages machine learning techniques to classify whether a loan should be approved or denied based on the applicant's profile.

### Dataset
The dataset includes the following features:
Numerical Features: Applicant age, income, employment experience, loan amount, interest rate, etc.
Categorical Features: Gender, education, home ownership, loan intent, credit score categories, etc.
### Project Steps
1. Data Loading and Preprocessing
Importing required libraries.
Loading the dataset and inspecting its structure.
Checking and addressing missing values and duplicates.

2. Exploratory Data Analysis (EDA)
Univariate Analysis: Understanding the distribution of individual variables.
Bivariate Analysis: Investigating relationships between features and the target variable.
Visualizations include histograms, bar plots, and correlation heatmaps.

3. Hypothesis Testing
Conducting statistical tests to validate relationships between variables.
Methods used include:
Analysis of variance (ANOVA)
Chi-square tests for categorical variables.

4. Feature Engineering
Handling outliers using the IQR method.
Encoding categorical variables.
Balancing the dataset using SMOTE (Synthetic Minority Oversampling Technique).

5. Model Training
Splitting data into training and testing sets.
Training the following models:
Logistic Regression
Random Forest with GridSearchCV
XGBoost Classifier with hyperparameter tuning.

6. Evaluation
Metrics used:
Confusion Matrix
Precision, Recall, and Accuracy
ROC-AUC Curve.
Cross-validation to ensure model reliability.

### Key Features
Comprehensive data preprocessing pipeline.
Statistical hypothesis testing for feature significance.
Multiple machine learning models with hyperparameter optimization.
Use of advanced techniques like SMOTE to address data imbalance.

### Results
Achieved high accuracy and ROC-AUC scores for predicting loan approvals.
Random Forest and XGBoost models performed robustly with consistent cross-validation results.
