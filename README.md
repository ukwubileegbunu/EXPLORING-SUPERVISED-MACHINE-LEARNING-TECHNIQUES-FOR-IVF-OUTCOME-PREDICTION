Project Overview
This project involves analyzing and predicting fertility outcomes using machine learning models. The dataset used is sourced from [Kagle's Fertility Dataset](https://www.kaggle.com/datasets/gabbygab/fertility-data-set). The primary goal is to predict whether a patient's diagnosis is classified as "Normal" or "Altered" based on clinical, behavioral, and demographic features.

Dataset Information
Source: Kaggle
Features: Includes demographic, clinical, and lifestyle variables such as:
Season (of fertility evaluation)
Age
Childish diseases (binary: 1 = Yes, 0 = No)
Surgical intervention (binary: 1 = Yes, 0 = No)
Smoking habit (binary: 1 = Yes, 0 = No)
High fevers in the last year
Number of hours spent sitting per day
Target Variable: Diagnosis (binary: Normal or Altered)


Key Steps in the Project
Data Preprocessing:

Handling Missing Values: No missing values were found in the dataset.
Feature Encoding: Categorical features were encoded into numeric values using label encoding for compatibility with machine learning algorithms.
Feature Selection: Variables were analyzed for correlation, and redundant or unnecessary features were excluded as needed.
Exploratory Data Analysis (EDA):

Visualized feature distributions using boxplots and bar plots.
Analyzed correlations between key numerical features.
Explored the relationship between features such as Age and Diagnosis.
Model Training and Evaluation:

Algorithms Used:
K-Nearest Neighbors (KNN)
Logistic Regression
Support Vector Machine (SVM)
Decision Tree Classifier
Evaluation Metrics:
Accuracy
Confusion Matrix
ROC-AUC Curve
Key Findings:
Logistic Regression and SVM achieved the highest accuracy (90%).
KNN and Decision Tree models performed slightly lower, with 85% accuracy.
Model Comparison:

A bar chart was used to compare the accuracy of different models, highlighting the best-performing algorithms.
