## Customer Churn Prediction

## Project Overview

This project predicts whether a customer is likely to leave a telecommunications company using machine learning. It uses customer information and service details to identify patterns related to churn.

## Objectives

- Analyze customer churn patterns.
- Perform data cleaning and exploratory data analysis (EDA).
- Build a Random Forest classification model.
- Apply SMOTE oversampling to address class imbalance.
- Evaluate and compare model performance.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Google Colab

## Project Workflow

1. Data loading and cleaning
2. Exploratory Data Analysis (EDA)
3. Data encoding
4. Train-test split
5. Random Forest model training
6. Model evaluation
7. SMOTE oversampling
8. Evaluation of the SMOTE model
9. Feature importance analysis

## Skills Demonstrated

Python, Data Cleaning, Exploratory Data Analysis, Data Visualization, Machine Learning, Classification, SMOTE, and Model Evaluation.

## Key Findings

- Customer churn can be predicted using customer and service information.
- The original model performed better at identifying customers who stayed.
- SMOTE helped identify more actual churners.
- Accuracy alone is not enough to evaluate a churn prediction model; recall and F1-score are also important.

  ## Visualization
  ## Churn Distribution
  <img width="812" height="751" alt="Screenshot 2026-10-27 153647" src="https://github.com/user-attachments/assets/c5384664-f0b7-47b6-a0ec-63cb7f3dd282" />
  
## Churn by Contract
<img width="1147" height="813" alt="Screenshot 2026-10-27 153734" src="https://github.com/user-attachments/assets/4b7412f1-ea37-4735-b569-14af54df9106" />

## Churn by Pymentmethod
<img width="842" height="827" alt="Screenshot 2026-10-27 153804" src="https://github.com/user-attachments/assets/0d7b5131-2f63-4d37-bed3-d1323e5f8941" />

## Feature Importance
<img width="747" height="755" alt="Screenshot 2026-10-27 153903" src="https://github.com/user-attachments/assets/206c8fa1-d454-4de4-bc05-c85ca09fdfb2" />


## Conclusion

This project demonstrates data cleaning, exploratory data analysis, feature encoding, machine learning, and model evaluation. It also explores how oversampling can affect the performance of a Random Forest classifier when predicting customer churn.SMOTE improved the model's ability to identify customers who churned, although overall accuracy decreased.

## Dataset

Kaggle Telco Customer Churn dataset.

