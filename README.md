# Breast_Cancer_Prediction

This project focuses on building and evaluating machine learning models to predict whether a tumor is benign or malignant based on medical diagnostic data. The dataset includes various features computed from breast mass images, such as radius, texture, smoothness, and concavity. Accurate prediction of breast cancer can assist doctors in early diagnosis and better treatment planning.

📂 Dataset

Source: Breast Cancer Wisconsin (Diagnostic) Dataset – UCI Machine Learning Repository / sklearn

Features: 30 numeric variables describing cell nuclei characteristics.

Target:

0 = malignant

1 = benign

Shape: ~569 samples × 30 features


🛠️ Steps in the Project

Data Exploration & Cleaning

Checked for missing values

Performed statistical summaries and correlations

Visualized feature distributions

Feature Engineering

Normalized / standardized features

Selected important variables using correlation and feature importance

Model Building

Algorithms tested:Random Forest

Model Evaluation

Metrics used: Accuracy, Precision, Recall, F1-score, ROC-AUC

Cross-validation applied to ensure robustness

📊 Results

Best Performing Model: Random Forest

Accuracy: ~95–98%

ROC-AUC: ~0.99

The model shows strong performance in distinguishing between malignant and benign cases.
