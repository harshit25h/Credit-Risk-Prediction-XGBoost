# Credit Risk Prediction using Logistic Regression and XGBoost

## Objective

The objective of this project is to predict customer creditworthiness using machine learning techniques and identify the key factors influencing credit risk.

---

## Business Problem

Financial institutions must assess whether a customer is likely to repay a loan. Incorrect lending decisions can result in significant financial losses due to loan defaults.

This project uses machine learning models to classify applicants as either:

- Good Credit Risk
- Bad Credit Risk

The analysis also identifies the most influential factors affecting creditworthiness.

---

## Dataset Information

### German Credit Dataset

| Attribute | Value |
|------------|--------|
| Total Records | 1000 |
| Features | 20 |
| Target Classes | Good Credit, Bad Credit |

### Target Distribution

| Class | Count |
|---------|---------|
| Good Credit | 700 |
| Bad Credit | 300 |

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- XGBoost
- Google Colab

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. Target Variable Encoding
5. One-Hot Encoding of Categorical Features
6. Train-Test Split
7. Model Training
   - Logistic Regression
   - XGBoost
8. Model Evaluation
9. Cross Validation
10. Feature Importance Analysis

---

## Data Preprocessing

The following preprocessing steps were performed:

- Checked dataset structure and data types
- Examined target variable distribution
- Converted target labels:
  - Good → 1
  - Bad → 0
- Applied One-Hot Encoding to categorical variables
- Split data into training and testing sets (80:20)

---

## Models Implemented

### 1. Logistic Regression

A baseline classification model used to predict customer credit risk.

### 2. XGBoost Classifier

A gradient boosting algorithm used to compare performance with Logistic Regression.

---

## Model Performance

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 79.5% |
| XGBoost | 77.5% |
| 5-Fold Cross Validation | 75.3% |

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Cross Validation Score

---

## Top Predictive Features

Based on Logistic Regression coefficient analysis, the most influential features were:

1. Credit History
2. Status of Checking Account
3. Foreign Worker Status
4. Purpose of Loan
5. Other Installment Plans
6. Secondary Obligor Information
7. Employment History

---

## Key Findings

- Logistic Regression achieved the highest accuracy on this dataset.
- Credit history was the strongest predictor of customer creditworthiness.
- Account status significantly influenced loan approval outcomes.
- Cross-validation confirmed that model performance remained stable across different data splits.
- Feature importance analysis provided interpretable business insights.

---

## Business Impact

Credit risk prediction can help financial institutions:

- Reduce loan default risk
- Improve lending decisions
- Identify high-risk applicants
- Optimize credit approval processes
- Improve portfolio management strategies

---

## Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- One-Hot Encoding
- Classification Modeling
- Logistic Regression
- XGBoost
- Model Evaluation
- Cross Validation
- Feature Importance Analysis
- Credit Risk Analytics

---

## Future Improvements

Potential enhancements include:

- Hyperparameter Tuning using GridSearchCV
- Random Forest Implementation
- ROC Curve Analysis
- AUC Score Evaluation
- Feature Scaling
- SHAP Explainability
- Streamlit Deployment
- Interactive Dashboard Development

---

## Repository Structure

```
Credit-Risk-Prediction-XGBoost/
│
├── Credit_Risk_Prediction_XGBoost.ipynb
├── german_credit_data.csv
└── README.md
```

---

## Author

**Harshit Marskole**  
M.Tech in Industrial Engineering and Operations Research (IEOR)  
Indian Institute of Technology Delhi (IIT Delhi)

---

## Project Status

✅ Completed
