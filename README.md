# 🏦 Loan Approval Prediction System

A Machine Learning project that predicts whether a loan application will be **approved or rejected** based on applicant details such as income, credit score, employment status, and financial history.

---

## 🚀 Project Overview

This project uses a real-world styled dataset to build a predictive model for loan approval decisions. It follows a complete ML pipeline including:

* Data Cleaning
* Missing Value Handling
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training & Evaluation

---

## 📂 Dataset Features

The dataset contains the following key attributes:

* Applicant Income
* Coapplicant Income
* Employment Status
* Age
* Marital Status
* Dependents
* Credit Score
* Existing Loans
* Debt-to-Income Ratio (DTI)
* Savings
* Collateral Value
* Loan Amount
* Loan Term
* Loan Purpose
* Property Area
* Education Level
* Gender
* Employer Category

🎯 **Target Variable:**

* `Loan_Approved` → Yes / No

---

## 🛠️ Tech Stack

* **Language:** Python 🐍
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn

---

## ⚙️ Workflow

### 1. Data Preprocessing

* Handled missing values using:

  * Mean (numerical features)
  * Mode (categorical features)

### 2. Feature Engineering

* Converted categorical variables using One-Hot Encoding
* Dropped unnecessary columns (e.g., Applicant_ID)
* Encoded target variable (Yes → 1, No → 0)

### 3. Model Building

* Used **Logistic Regression** as baseline model

### 4. Model Evaluation

* Accuracy Score
* Classification Report (Precision, Recall, F1-score)

---

## 📊 Results

* Achieved reliable prediction performance using Logistic Regression
* Identified important factors affecting loan approval:

  * Credit Score 📈
  * Income 💰
  * Debt-to-Income Ratio ⚖️
  * Collateral Value 🏠

---

## 📌 Key Insights

* Higher credit scores significantly increase approval chances
* High DTI ratio reduces approval probability
* Applicants with stable income sources (salaried) perform better
* Savings and collateral play a crucial role

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/loan-approval-prediction.git
cd loan-approval-prediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## 📈 Future Improvements

* Implement advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy as a web app (React + Flask)
* Add real-time prediction interface
* Improve feature engineering

---

## 💡 Use Cases

* Banking & Financial Institutions
* Credit Risk Analysis
* Loan Automation Systems
* FinTech Applications

---

## 👨‍💻 Author

**Abhiram Modukuru**

* AIML Student | Aspiring Entrepreneur
* Passionate about ML, Data Science & Building Real-World Projects

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!

---
