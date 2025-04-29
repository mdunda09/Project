# Project
This project was developed as part of a supervised machine learning assignment focused on predicting breast cancer survival outcomes. The goal was to explore, preprocess, and analyze a clinical dataset, handle class imbalance, and evaluate multiple classification algorithms using fair and robust performance metrics.

The dataset contains anonymized patient information with various categorical and numerical features, and the target variable indicates whether the patient is alive or deceased. Due to the imbalance in class distribution, special techniques like SMOTENC oversampling and cost-sensitive learning were applied and compared using a statistical hypothesis test.

We trained and evaluated four machine learning models:

Random Forest (Ensemble model)

XGBoost (Gradient Boosting)

Support Vector Machine (with Grid Search)

K-Nearest Neighbors (with Random Search)

Each model was assessed using Balanced Accuracy, Confusion Matrix, ROC Curve, and other metrics across training, validation, and test sets.
