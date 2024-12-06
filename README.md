# Customer-Churn-Prediction
## Overview
This project focuses on predicting customer churn in the telecommunications industry using machine learning models. The goal is to build and evaluate different machine learning models to predict whether a customer will churn based on their attributes. The dataset used contains 7043 rows and 21 columns, and we aim to analyze the data, build models, and evaluate performance based on various metrics such as accuracy, precision, recall, and F1-score.
## Project Steps
1. **Data Preprocessing:**
   - Handling missing, null, and NaN values.
   - Identifying and handling outliers.
   - Data transformation to ensure all entries are numeric.
   
2. **Data Exploration:**
   - Identifying types of data: numeric, categorical, and text.
   - Performing exploratory data analysis (EDA) to understand feature relationships.
   - Identifying important features affecting customer churn.

3. **Model Building:**
   - Applying various machine learning models:
     - Naïve Bayes
     - Logistic Regression
     - Random Forests
     - XGBoost
   - Evaluating models on accuracy, precision, recall, and F1-score.
   - Using SMOTE technique to handle data imbalance.

4. **Model Evaluation:**
   - Split the dataset into training and testing sets (80/20).
   - Use SweetViz to compare the training and test datasets with respect to the target variable ('churn').

5. **Limitations:**
   - Discuss any issues or limitations encountered with the dataset or model performance.

## Requirements
To run this project, the following Python libraries are required:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
- `imbalanced-learn`
- `sweetviz`
