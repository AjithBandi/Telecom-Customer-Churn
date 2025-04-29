# Telecom-Customer-Churn
A Python project to predict telecom customer churn using machine learning
# Customer Churn Prediction

A Python project to predict telecom customer churn using machine learning, built as part of my data science portfolio.

## Overview
This project uses the Telco Customer Churn dataset to predict which customers might leave a telecom company. 
It includes data cleaning, predictive modeling, and visualization of key churn factors.

## Features
- **Accuracy**: Achieved 78% with logistic regression.
- **Models**: Logistic regression (78%) and decision tree (72%).
- **Key Insights**: Tenure and two-year contracts reduce churn; high monthly charges increase it.

## Tools
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook

## Dataset
- Source: [Telco Customer Churn on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Included in repo (or download from link if not uploaded).

## How to Run
1. Download the repo files.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook: `jupyter notebook churn_prediction.ipynb`
4. Run all cells to see the analysis.

## Results
- Logistic Regression: 78% accuracy, highlighted tenure as the top retention factor.
- Decision Tree: 72% accuracy, visualized decision splits.
