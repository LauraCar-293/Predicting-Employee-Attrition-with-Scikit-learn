# Scikit-learn: prediction on employee attrition

This project focuses on predicting employee attrition—a binary outcome indicating whether an employee leaves 
the company unexpectedly, often due to burnout. The analysis involved building and evaluating machine learning 
models to identify patterns and improve predictive performance.

All preprocessing steps and model training were integrated using pipelines to ensure a clean and
 reproducible workflow. Several classification models were developed and compared, including:

- K-Nearest Neighbors (KNN)

- Decision Tree Classifier

- Dummy Classifier (used as a baseline)

Before model comparison, hyperparameter optimization (HPO) was conducted for each model using cross-validation 
on the training set. Multiple data preprocessing strategies were explored, including Min-Max Scaling and Standard Scaling, 
to assess their impact on model performance.

## Tools

The project was developed in Python using scikit-learn (sklearn) as the main library for preprocessing, modeling, and evaluation.