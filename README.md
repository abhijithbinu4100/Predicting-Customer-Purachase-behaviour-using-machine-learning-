# Predicting-Customer-Purachase-behaviour-using-machine-learning-
Project Overview

This repository contains my Master's Thesis completed as part of the Master of Science (MSc.) in Data Science (120 ECTS). The research focuses on predicting customer purchase behavior using machine learning algorithms to help businesses design more effective and personalized marketing strategies.

The project explores how historical customer data can be analyzed to identify purchasing patterns and predict whether a customer is likely to make a high-value purchase. By leveraging predictive analytics and explainable artificial intelligence (XAI), this research demonstrates how machine learning can support data-driven business decisions while maintaining model transparency.

Objectives

The primary objectives of this project are:

Analyze customer shopping behavior using a real-world dataset.
Compare the performance of multiple machine learning algorithms.
Identify the most influential factors affecting customer purchasing decisions.
Develop an interpretable prediction system using Explainable AI techniques.
Demonstrate how prediction results can be translated into personalized marketing strategies.
Dataset

The project uses the Consumer Behavior and Shopping Habits dataset obtained from Kaggle. The dataset contains approximately 3,900 customer transactions with 18 attributes, including demographic information, purchase history, payment methods, product categories, subscription status, review ratings, shipping methods, and seasonal purchasing information.

Data Preprocessing

Several preprocessing techniques were applied before model training:

Missing value analysis
Label encoding for categorical variables
Feature normalization using Z-score standardization
Outlier detection using box plots
Correlation analysis
Feature importance analysis using SHAP

These preprocessing steps improved data quality and prepared the dataset for reliable machine learning model development.

Machine Learning Models

This project evaluates multiple machine learning algorithms, including:

Logistic Regression
Decision Tree Classifier
Support Vector Machine (SVM)
Gaussian Naïve Bayes
Multi-Layer Perceptron (MLP)
Random Forest
XGBoost
LightGBM

The models were compared using multiple evaluation metrics to identify the most suitable approach for customer purchase prediction.

Model Evaluation

The trained models were evaluated using standard machine learning performance metrics, including:

Accuracy
Precision
Recall
F1 Score
ROC Curve
Area Under the Curve (AUC)

These metrics provide a comprehensive assessment of predictive performance and model reliability.

Explainable Artificial Intelligence (XAI)

To improve transparency and interpretability, this research incorporates two widely used Explainable AI techniques:

SHAP (SHapley Additive exPlanations)
LIME (Local Interpretable Model-agnostic Explanations)

These methods explain how different features influence model predictions, making the results easier to understand and more useful for business decision-makers.

Business Applications

The findings of this research can support organizations in:

Personalized marketing campaigns
Customer segmentation
Purchase prediction
Customer retention strategies
Marketing budget optimization
Data-driven business decision-making

The project demonstrates how machine learning can help organizations better understand customer behavior and improve engagement through personalized marketing strategies.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
XGBoost
LightGBM
Matplotlib
Seaborn
SHAP
LIME
Jupyter Notebook
Repository Contents
Thesis Report (PDF)
Source Code
Jupyter Notebooks
Dataset (if redistribution is permitted)
Model Files
Visualizations
Documentation
Author

Abhijith Binu
