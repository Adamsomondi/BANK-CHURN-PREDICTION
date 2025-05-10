# BANK-CHURN-PREDICTION

## Dataset Source

https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers

## Description

This project leverages bank customer churn dataset and classification machine learning techniques to accurately predict customer churn, enabling proactive decision-making and improved customer retention
The project goal is to use this model to help the bank to retain its customers since Customers switching from one company to another  makes the company loose revenue.

## Features
- Customer demographic analysis
- Behavioral pattern recognition
- Machine learning-based prediction
- Data visualization and insights
- Predictive model performance metrics

## Installation
1. Clone the repository
```bash
git clone https://github.com/Adamsomondi/BANK-CHURN-PREDICTION.git
```

2. Install required dependencies
```bash
pip install -r requirements.txt
```

## Usage
1. Open the Jupyter notebook
```bash
jupyter notebook
```
2. Navigate to the main notebook file
3. Follow the step-by-step analysis and model building process

## Model Features
The model considers various customer attributes including:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Member Status
- Estimated Salary

## Modeling

### Model Selection

Two classification models were evaluated:

- **Logistic Regression**
- **Random Forest Classifier**

Both models performed exceptionally well on the test dataset:

| Metric              | Logistic Regression | Random Forest |
|---------------------|---------------------|---------------|
| Accuracy            | 0.999               | 0.999         |
| F1-Score            | 0.999               | 0.999         |

- **True Negatives (TN)**: 1606 — Class 0 correctly predicted  
- **False Positives (FP)**: 1 — Class 0 incorrectly predicted as Class 1  
- **False Negatives (FN)**: 1 — Class 1 incorrectly predicted as Class 0  
- **True Positives (TP)**: 392 — Class 1 correctly predicted  

This confusion matrix highlights the model's near-perfect classification ability, with only two misclassifications out of 2000 total samples. The low number of false positives and false negatives suggests strong precision and recall for both classes.

 ## Cross-Validation
To ensure robustness, 5-fold cross-validation was performed on both models:

Logistic Regression Mean Accuracy: 0.9986

Random Forest Mean Accuracy: 0.9986

Standard Deviation (both models): ~0.00196

Despite identical cross-validation metrics,
Random Forest was selected as the final model due to its strong performance and robustness to feature scaling and outliers.

## Contact
- Medium Link: 













