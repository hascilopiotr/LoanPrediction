Credit Risk Prediction System
This project implements a machine learning pipeline to predict loan default risk based on client demographic and financial data. It includes exploratory data analysis, model training and model deployment

Project Overview
The goal is to classify loan applicants into risk categories (Accept, Review, Reject) based on the probability of default. The model is trained on an imbalanced dataset, utilizing class weighting and threshold tuning to optimize for Precision-Recall AUC.

Features
Data cleaning and preprocessing (One-Hot Encoding, Scaling).

Model comparison: Logistic Regression, Random Forest, Gradient Boosting.

Evaluation using Precision-Recall AUC and Confusion Matrix.

Business logic implementation for decision making.

Model Performance
The Random Forest Classifier was selected as the final model. It utilizes a custom probability threshold of 0.35 to maximize the detection of high-risk clients while maintaining a balance between precision and recall.
