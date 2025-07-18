# loan_prediction_classification

# 🏦 Loan Prediction Classification

This project aims to predict whether a loan will be approved or not based on customer details using various classification algorithms. The goal is to identify the best-performing model for maximum prediction accuracy.

---

## 📁 Dataset

**File:** `loan_prediction.csv`

The dataset includes features such as:
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Gender, Married, Education, Self_Employed
- Property_Area
- Dependents
- Target Variable: `Loan_Status` (Y/N or 1/0)

---

## 🔍 Problem Statement

Given a set of features about loan applicants, predict whether a loan will be approved (`Loan_Status`) using machine learning classification models.

---

## 🔧 Technologies Used

- Python 3.x
- pandas, numpy
- scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📊 Model Workflow

1. **Load and Inspect Data**
2. **Preprocess Data**
   - Fill missing values
   - Encode categorical variables
   - Feature scaling using `StandardScaler`
3. **Train/Test Split**
4. **Train Models**
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
   - XGBoost
5. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
6. **Select Best Model** based on accuracy

