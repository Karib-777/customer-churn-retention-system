# Customer Churn Prediction and Retention Decision System

## Project Overview

This project uses machine learning to predict customer churn from customer demographic, account, service, and billing information.

The objective is to identify customers who may be at risk of leaving and investigate how churn predictions can support customer retention decisions.

## Business Problem

Customer churn can affect recurring revenue and increase the cost of acquiring replacement customers. Predictive analytics can help businesses identify patterns associated with churn and prioritize customers for further investigation.

## Objectives

- Explore and clean customer data.
- Perform exploratory data analysis and visualization.
- Train and compare machine-learning classification models.
- Evaluate models using appropriate classification metrics.
- Investigate the factors associated with predicted churn.
- Explore customer prioritization under different outreach budgets.

## Dataset

The project uses the IBM Telco Customer Churn dataset.

Source: https://github.com/IBM/telco-customer-churn-on-icp4d

Review the source repository's terms and dataset information before redistributing the data.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git and GitHub

## Project Structure

```text
customer-churn-retention-system/
├── data/
├── notebooks/
├── src/
├── reports/
└── app/
```

## Current Status

Project in development.

Planned stages include data exploration, preprocessing, model training, evaluation, and an interactive dashboard.

## Evaluation

The planned evaluation metrics include ROC-AUC, precision, recall, F1-score, and precision-recall AUC. Probability calibration and outreach-budget analysis will be investigated where appropriate.

## Limitations

Predictions indicate estimated churn risk, not certainty that a customer will leave. Predictive associations do not establish causation. Any retention or financial benefit estimates must be clearly distinguished from observed business outcomes.

## Author

Add your name and professional profile here after reviewing the project.