# Task 3: Heart Disease Prediction

## Objective
Build a machine learning model to predict whether a person is at risk of heart disease based on clinical data.

## Dataset
- Source: UCI Heart Disease Dataset (Cleveland subset)
- Columns: age, sex, chest pain type, blood pressure, cholesterol, max heart rate, etc.
- Target: 1 (disease) or 0 (no disease)

## Tools Used
- Python
- Jupyter Notebook
- pandas, seaborn, matplotlib
- scikit-learn (Logistic Regression)

## Preprocessing
- Converted multiclass target to binary:
  - 0 = no disease
  - 1 = presence of disease

## Evaluation
- Accuracy
- Confusion Matrix
- ROC Curve and AUC score

## Insights
Logistic Regression achieved decent classification results. Further tuning and feature scaling could improve performance. Visualization of ROC and confusion matrix helped interpret model reliability.
