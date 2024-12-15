# Customer Churn Prediction for Vodafone Idea

This project focuses on predicting customer churn for Vodafone Idea, leveraging machine learning to identify at-risk customers and enable data-driven retention strategies.

## Executive Summary

- **Objective**: Predict customer churn using customer data to improve retention rates.
- **Market Context**: 
  - The Indian telecom market is highly competitive and price-sensitive.
  - Recent trends show increased churn due to tariff changes by competitors.
- **Solution**: A machine learning model was developed to analyze customer behavior and predict churn likelihood.

## Project Overview

### Data Preparation
- Conducted Exploratory Data Analysis (EDA) to uncover trends and patterns.
- Applied data transformations to optimize the dataset for model performance.

### Algorithms Evaluated
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Logistic Regression (chosen as the final model)
- K-Nearest Neighbors (KNN)

### Model Selection
**Logistic Regression** was selected due to its:
- High efficiency in binary classification.
- Ability to handle imbalanced datasets effectively.
- Clear probability estimates for churn likelihood.
- Balanced precision and recall metrics.

## Model Performance

### Key Metrics
- **Training Accuracy**: 92.14%
- **Test Accuracy**: 90.00%
- **Class 1 (Churned Customers)**:
  - Precision: 94.54%
  - Recall: 65.82%
  - F1-Score: 77.61%
- **Class 0 (Non-Churned Customers)**:
  - Recall: 98.64%
  - Precision: 88.98%

### Observations
- The model excels at identifying non-churned customers but requires improvement in recall for churned customers.
- The AUC-ROC curve shows strong predictive power with low false positives and high true positives.

## Benefits of the Model
- **Risk Reduction**: Minimizes customer loss by identifying at-risk customers.
- **Efficiency**: Improves operational decision-making.
- **Sustainable Growth**: Supports retention and market competitiveness.

## Repository Contents
- `Customer Churn Prediction for Vodafone Idea.pptx`: A presentation summarizing the project and results.
- `Customer Churn VI.ipynb`: Jupyter notebook with implementation details and code.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/jubiranka/Customer-Churn-Analysis-for-VI
