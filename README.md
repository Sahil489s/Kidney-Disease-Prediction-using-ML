# Kidney-Disease-Prediction-using-ML
This project aims to develop a reliable machine learning model for early detection of Chronic Kidney Disease (CKD). Leveraging a variety of supervised learning algorithms, this tool can assist healthcare professionals by predicting the likelihood of CKD based on clinical parameters.

📚 Table of Contents
Overview

Dataset

Technologies Used

Project Pipeline

Model Performance

How to Run

Future Enhancements

Author

License

🧾 Overview
Chronic Kidney Disease is a progressive condition that can be life-threatening if not diagnosed early. The goal of this project is to use machine learning techniques to predict CKD based on patient data, enabling early intervention and better health outcomes.

📊 Dataset
Source: UCI Machine Learning Repository

Samples: 400

Features: 26 (includes clinical and laboratory parameters)

Target: ckd or notckd

⚙️ Technologies Used
Python

Pandas, NumPy – Data processing

Matplotlib, Seaborn – Visualization

Scikit-learn – Machine Learning

Jupyter Notebook – Development environment

🔁 Project Pipeline
1. Data Preprocessing
Missing value imputation

Label encoding for categorical variables

Feature normalization

2. Exploratory Data Analysis (EDA)
Correlation analysis

Feature distributions

Class imbalance checks

3. Model Training & Tuning
Implemented and compared the performance of:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Gradient Boosting Classifier (GBC)

Hyperparameter tuning was performed using GridSearchCV.

4. Model Evaluation
Accuracy, Precision, Recall, F1-Score

Confusion Matrix

ROC-AUC Curve

✅ Model Performance
Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	96.0%	96.5%	95.8%	96.1%
Random Forest	98.0%	98.2%	97.9%	98.0%
Gradient Boosting	99.0%	99.1%	98.9%	99.0%

Gradient Boosting Classifier delivered the best overall performance.

