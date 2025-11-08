# 🏦 Loan Prediction

This project aims to **analyze loan data and predict loan approval** based on applicant information using machine learning techniques.  
It includes data preprocessing, model training, performance evaluation, and MLflow tracking for experiment management.

---

## 📊 Project Overview

The goal of this project is to develop a predictive model that determines whether a loan application should be approved or not.  
Two supervised learning algorithms were implemented and compared:

- **Logistic Regression**
- **Decision Tree Classifier**

Additionally, **MLflow** was used to track and log experiments, making it easier to monitor metrics, parameters, and artifacts.

---

## 🧠 Workflow

### 1. Data Preprocessing
- Converted categorical variables into numerical form.  
- Handled missing values in key features such as `LoanAmount`.  
- Created new feature `TotalIncome` from `ApplicantIncome` and `CoapplicantIncome`.  
- Split the data into training and testing sets.
- Apply SMOTE
- Scaling the data by RobustScaler

### 2. Model Training
- Built and trained both Logistic Regression and Decision Tree models.
- Tuned hyperparameters to improve accuracy and generalization.

### 3. Model Evaluation
- Evaluated models using key performance metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

### 4. Experiment Tracking with MLflow
- Each experiment (model training run) was tracked using **MLflow**.
- Logged:
  - Model parameters
  - Evaluation metrics
  - Trained model artifacts
- Enabled comparison between models directly through the MLflow UI.

---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/DoaaHazem/Machine_Learning_4.git
