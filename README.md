# Customer-Churn-Prediction
Predict which customers are likely to churn using Machine Learning (Logistic Regression, Random Forest, XGBoost)

# Customer Churn Prediction

Predict which customers are likely to churn using Machine Learning.

## Dataset
Columns include customer demographics, services, billing info, and churn label.

## Steps
1. Exploratory Data Analysis (EDA)
2. Data Preprocessing
3. Modeling using Logistic Regression, Random Forest, XGBoost
4. Model Evaluation: Accuracy, Recall, ROC-AUC

## Usage
```python
# Example
import pandas as pd
import xgboost as xgb

# Load data
df = pd.read_csv('data/Telco-Customer-Churn.csv')

# Train model (example)
