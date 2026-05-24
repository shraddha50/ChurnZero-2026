# ChurnZero-2026
Bank Customer Churn Prediction using Machine Learning
# ChurnZero 2026 - Banking Customer Churn Prediction

## Team Members
- Shraddha Sharma
- Niharika Pareek

---

# Problem Statement

Customer churn is one of the biggest challenges faced by banks and financial institutions. Retaining existing customers is significantly more cost-effective than acquiring new ones.

The objective of this project is to build a machine learning model capable of accurately predicting customer churn using customer behavior, financial activity, and engagement metrics.

---

# Objective

Develop a predictive system that:
- Identifies high-risk customers
- Helps banks take proactive retention actions
- Minimizes financial loss caused by customer churn

---

# Dataset Overview

## Training Dataset
- Rows: 8101
- Features: 97+

## Test Dataset
- Rows: 2026

The dataset contains:
- Customer demographics
- Banking activity
- Digital engagement
- Transaction behavior
- Financial indicators
- Feedback metrics
- Customer relationship information

---

# Machine Learning Workflow

## 1. Data Preprocessing
- Removed identifier columns
- Handled missing values
- Encoded categorical variables using Label Encoding
- Performed train-validation split using stratification
- Prevented data leakage

---

## 2. Exploratory Data Analysis
Performed:
- Churn distribution analysis
- Missing value analysis
- Feature importance analysis
- Customer behavior pattern analysis

---

## 3. Model Selection

### Model Used
- Random Forest Classifier

### Why Random Forest?
- Handles mixed feature types effectively
- Robust against overfitting
- Performs well on structured/tabular datasets
- Supports feature importance analysis

---

# Evaluation Metrics

The project was evaluated using:

| Metric | Score |
|---|---|
| F1 Score | 0.984 |
| PR-AUC Score | 0.998 |

---

# Business Cost Framing

The business objective prioritizes minimizing False Negatives because:

- False Negative Cost = ₹40,000
- False Positive Cost = ₹500

Missing an actual churner results in significantly higher financial loss. Therefore, the model focuses on maximizing recall and PR-AUC performance.

---

# Key Business Insights

## Major Churn Drivers
- Declining account balances
- Reduced transaction activity
- Lower digital engagement
- Reduced monthly transaction value
- Low relationship manager interaction

---

# Top Important Features

- total_digital_logins
- total_trans_count
- balance_decline_percentage
- avg_quarterly_balance
- current_balance
- avg_monthly_balance
- cash_withdrawal_count
- relationship_manager_interaction_count
- monthly_transaction_count
- monthly_transaction_value

---

# Business Recommendations

## 1. Early Churn Warning System
Identify customers showing:
- declining balances
- low engagement
- reduced transactions

and trigger proactive retention campaigns.

---

## 2. Personalized Retention Campaigns
Provide:
- personalized offers
- fee waivers
- loyalty rewards
- relationship manager outreach

for high-risk customers.

---

## 3. Improve Digital Engagement
Encourage:
- mobile banking usage
- digital transactions
- personalized notifications

to increase retention.

---

## 4. Protect High-Value Customers
Customers with:
- high balances
- high transaction values

should receive priority retention strategies.

---

# Repository Files

| File | Description |
|---|---|
| ChurnZero_Final.ipynb | Complete ML workflow |
| ChurnZero_Team_Predictions.csv | Final churn predictions |
| Presentation.pdf | Final project presentation |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

# Conclusion

The developed churn prediction model achieved extremely high predictive performance and successfully identified major customer churn indicators.

The solution can help financial institutions:
- reduce churn-related losses
- improve customer retention
- optimize marketing efforts
- improve customer engagement strategies

---

# GitHub Repository

This repository contains:
- reproducible notebook
- prediction outputs
- business insights
- final presentation

---

# Thank You
[ChurnZero_Final.ipynb](https://github.com/user-attachments/files/28196701/ChurnZero_Final.ipynb)
[ChurnZero_Team_Predictions.csv](https://github.com/user-attachments/files/28196696/ChurnZero_Team_Predictions.csv)

