# Predicting Loan Default Risk

## Project Overview

Financial institutions face significant challenges in assessing the creditworthiness of loan applicants. This project aims to build a machine learning model that predicts the risk of loan defaults, helping financial institutions reduce default risks and improve portfolio performance.

## Objectives

1. **Data Exploration and Preprocessing:**
   - **Dataset:** The dataset contains loan applicant data such as credit history, income, employment status, and loan amount.
   - **Preprocessing:** Techniques such as handling missing values, feature scaling using `MinMaxScaler`, and balancing the data using SMOTE were applied.

2. **Model Development:**
   - Multiple models were developed including:
     - Logistic Regression
     - Decision Tree Classifier
     - Random Forest Classifier
     - Gradient Boosting Machines
     - XGBoost Classifier
   - Cross-validation and hyperparameter tuning were performed to optimize model performance.

3. **Evaluation:**
   - Models were evaluated using the following metrics:
     - Accuracy
     - Precision
     - Recall
     - F1-Score
     - ROC-AUC Score
   - Confusion matrices were used to assess the performance, focusing on precision-recall trade-offs to balance risk and reward.

4. **Actionable Insights:**
   - Key features impacting loan default risk were identified, such as credit history and loan amount.
   - Recommendations were made on how financial institutions can integrate these models into their loan approval processes to enhance decision-making and risk management.
