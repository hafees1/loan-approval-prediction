# 🏦 Loan Approval Prediction using Machine Learning

## 📌 Overview

This project is an end-to-end machine learning pipeline that predicts whether a loan application will be approved based on an applicant's financial and personal information.

The project covers the complete ML workflow, including data preprocessing, feature engineering, model training, evaluation, and prediction on unseen data.

---

## 📂 Dataset

**Source:** Kaggle - Loan Prediction Problem Dataset

https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset/data

The dataset contains information such as:

* Gender
* Marital Status
* Dependents
* Education
* Self Employment Status
* Applicant Income
* Coapplicant Income
* Loan Amount
* Loan Amount Term
* Credit History
* Property Area

The target variable is:

* **Loan_Status**

  * **Y** → Loan Approved
  * **N** → Loan Rejected

---

## 🎯 Objective

Build a machine learning model capable of predicting loan approval for new applicants using historical loan application data.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Train-Validation Split
4. Missing Value Imputation
5. One-Hot Encoding of Categorical Features
6. Feature Scaling using StandardScaler
7. Logistic Regression Model Training
8. Model Evaluation on Validation Set
9. Prediction on Unseen Test Data

---

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

* Handled missing numerical values using the **mean of the training set**
* Handled missing categorical values using the **mode of the training set**
* Applied **One-Hot Encoding** to categorical features
* Aligned validation and test features with the training feature set
* Standardized numerical features using **StandardScaler**
* Prevented **data leakage** by fitting preprocessing steps only on the training data

---

## 🤖 Machine Learning Model

**Algorithm Used**

* Logistic Regression

The model was trained using the processed training dataset and evaluated using a separate validation dataset.

---

## 📈 Results

The trained model was able to predict loan approval status on unseen validation and test data after completing the preprocessing pipeline.

---

## 📁 Repository Structure

```
├── loan_approval_prediction.ipynb
├── README.md
└── (dataset files)
```

---

## 📚 Key Learning Outcomes

Through this project, I learned:

* Building an end-to-end machine learning workflow
* Performing Exploratory Data Analysis (EDA)
* Handling missing values correctly
* Preventing data leakage
* Encoding categorical variables
* Feature scaling
* Training and evaluating classification models using Scikit-learn

---

## ⚠️ Note

This project was created for educational purposes using the original Kaggle dataset. Some features (such as demographic information) are included because they are part of the dataset. In real-world machine learning systems, sensitive features should be evaluated carefully for fairness, ethics, and compliance with applicable regulations before being used in decision-making models.
