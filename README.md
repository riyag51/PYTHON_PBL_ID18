❤️ Heart Disease Prediction System

A machine learning-based system that predicts the risk of heart disease using patient clinical and lifestyle data.

📌 Overview

This project uses multiple machine learning algorithms to analyze health parameters such as age, blood pressure, cholesterol, BMI, and lifestyle habits to predict whether a person is at high risk or low risk of heart disease.

The system includes:

Data preprocessing (missing values, encoding, scaling, outliers)
Model training and evaluation
User input-based prediction system
📊 Dataset Features

The dataset contains the following attributes:

AGE – Age of the individual
BP – Blood Pressure
CHOLESTROL – Cholesterol level
gender – Male/Female
bmi – Body Mass Index
family_history – Yes/No
smoking_status – Yes/No
alcohol_consumption – Low/Moderate/High
physical_activity – Low/Moderate/High
stress_level – Low/Moderate/High
sleep_hours – Daily sleep duration
diabetes – 0/1
hypertension – Target variable (0/1)
⚙️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
🤖 Machine Learning Models

The following classification models were implemented:

Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Decision Tree
📈 Evaluation Metrics

Models were evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
🔧 Project Workflow
Data Collection
Data Cleaning (handling null values)
Outlier Detection (IQR method)
Encoding Categorical Variables
Feature Scaling (StandardScaler)
Model Training
Model Evaluation
Best Model Selection
User Input Prediction
