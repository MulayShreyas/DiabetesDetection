# Overview

This repository contains the implementation of a diabetes detection system utilizing machine learning algorithms. The goal is to predict whether a patient has diabetes based on diagnostic measurements. The dataset used for this project is the PIMA Indians Diabetes Database, which includes various medical predictor variables and one target variable indicating the presence of diabetes.


# Features

 1) Data Preprocessing: Handling missing values, data normalization, and feature selection.
 2) Exploratory Data Analysis (EDA): Visualizations and statistical analysis to understand data distribution and relationships.
 3) Model Training: Implementation of various machine learning algorithms including Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, Support Vector Machine, and Neural Networks.
 4) Model Evaluation: Assessing the performance of the models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
 5) Hyperparameter Tuning: Optimizing model parameters using techniques like Grid Search and Random Search.
 6)  Deployment: Exporting the trained model for deployment in a real-world scenario using tools like Flask or FastAPI.

# Dataset

The dataset used in this project is the PIMA Indians Diabetes Database. It includes the following features:
 1) Pregnancies: Number of times pregnant
 2) Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
 3) Blood Pressure: Diastolic blood pressure (mm Hg)
 4) Skin Thickness: Triceps skin fold thickness (mm)
 5) Insulin: 2-Hour serum insulin (mu U/ml)
 6) BMI: Body mass index (weight in kg/(height in m)^2)
 7) Diabetes Pedigree Function: Diabetes pedigree function
 8) Age: Age (years)
 9) Outcome: Class variable (0 or 1) where 1 indicates the presence of diabetes and 0 indicates absence
