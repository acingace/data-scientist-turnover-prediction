# data-scientist-turnover-prediction
This repository contains a machine learning project aimed at predicting whether data scientist candidates will change jobs after completing training programs conducted by a company. 

The dataset used is sourced from Kaggle and includes information on candidates' backgrounds, experience, and job history. 

To make predictions, three classification models were implemented and tuned: Logistic Regression, Random Forestl, and LightGBM. The LightGBM model achieved the best performance with a ROC UC of 0.9053, demonstrating strong predictive ability. 

## Dataset:
https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists

## Project Structure:
job-change-prediction.ipynb — Jupyter Notebook containing the full analysis, preprocessing, modeling, and evaluation.
README.md — Project overview and documentation.

## Model Performance Summary

| Model                   | Accuracy | Precision | Recall  | F1-Score | ROC AUC | PR AUC  |
|-------------------------|----------|-----------|---------|----------|---------|---------|
| Logistic Regression      | 0.7449   | 0.4914    | 0.6565  | 0.5621   | 0.7739  | 0.5149  |
| Random Forest Classifier | 0.7940   | 0.5794    | 0.6345  | 0.6057   | 0.8249  | 0.5995  |
| LightGBM Classifier      | 0.8439   | 0.6924    | 0.6728  | 0.6825   | 0.9053  | 0.7683  |
