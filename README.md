# Customer Churn Prediction

A machine learning project focused on predicting customer churn for a bank. This repository contains all steps from data exploration to model deployment.

---

## Project Overview

Customer churn is a critical issue for banks. Retaining existing customers is more cost-effective than acquiring new ones. This project uses historical customer data to predict which customers are likely to leave, enabling proactive retention strategies.

---

## Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- LightGBM (LGBMClassifier)
- GridSearchCV
- ROC-AUC, Precision, F1 Score

---

## Exploratory Data Analysis (EDA)

- Statistical summaries and correlation analysis
- Distribution plots for key variables
- Categorical encoding and missing value treatment
- Feature selection based on correlation and importance

---

## Preprocessing

- One-hot encoding of categorical variables
- Standardization of numerical features
- Train-test split (stratified)
- Balancing target class if needed

---

## Model Development

Multiple models were tested including:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- LightGBM

**Best Model:** `LGBMClassifier`  
- Learning Rate: `0.05`  
- Max Depth: `5`  
- Estimators: `100`

---

## Performance Metrics (on Test Data)

| Metric        | Score   |
|---------------|---------|
| Accuracy      | 0.8670  |
| Precision     | 0.7571  |
| F1 Score      | 0.5844  |
| ROC-AUC       | 0.8741  |

The model shows strong ability to distinguish between churn and non-churn cases, though further improvement is possible, especially with ensemble techniques.

---
## Author

**Ashok Racindran**  
Data Analyst | SQL | Python | Power BI  
*Email: ashokvravindran@gmail.com*  
*LinkedIn: https://www.linkedin.com/in/ashok--r/*

