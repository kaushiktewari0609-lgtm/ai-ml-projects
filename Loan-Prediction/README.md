# 🏦 Loan Status Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict whether a loan application will be approved or rejected using Machine Learning classification techniques.

The objective is to assist financial institutions in automating the loan approval process by analyzing applicant information and predicting loan eligibility based on historical data.

---

## 🎯 Problem Statement

Build a predictive model that determines whether a loan application is likely to be approved based on applicant details such as income, education, employment status, marital status, and credit history.

The target variable is:

- **Loan_Status**
  - Y → Loan Approved
  - N → Loan Rejected

---

## 📊 Dataset

The project uses the **Loan Prediction Dataset**.

Target Variable:

- **Loan_Status**

Dataset features include:

- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status

### Dataset Usage

The dataset file (`train.csv`) is included in this project repository.

To run the notebook successfully, ensure that the dataset file is located in the same directory as `Loan_Status_Prediction.ipynb`.

If you are using Google Colab, upload the dataset file before executing the notebook.

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow

1. Data Collection
2. Data Loading
3. Data Cleaning
4. Handling Missing Values
5. Exploratory Data Analysis (EDA)
6. Data Encoding
7. Feature Selection
8. Train-Test Split
9. Model Training
10. Model Evaluation
11. Prediction System Development

---

## 🤖 Machine Learning Model Used

The following classification algorithm was used:

- Support Vector Machine (SVM)

### Model Configuration

- Kernel: Linear
- Train-Test Split for model evaluation
- Accuracy Score used as the evaluation metric

---

## 📈 Model Performance

The Support Vector Machine classifier was trained and evaluated on both training and testing datasets.

Performance was measured using:

- Training Accuracy
- Testing Accuracy

The model demonstrated good predictive capability in determining loan approval status based on applicant information.

---

## 📸 Visualizations

The project includes various visualizations to better understand the dataset and identify patterns affecting loan approval decisions.

Visualizations include:

- Loan Status Distribution
- Education vs Loan Status
- Marital Status vs Loan Status
- Credit History Analysis
- Property Area Distribution
- Applicant Income Analysis
- Feature Relationship Analysis

Screenshots are available in the **images** folder.

---

## 🚀 How to Run the Project

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```text
Loan_Status_Prediction.ipynb
```

---

## 🎯 Future Improvements

- Perform hyperparameter tuning for improved accuracy
- Compare SVM with other classification algorithms
- Implement ensemble learning techniques
- Build an interactive web application using Streamlit
- Deploy the model for real-time loan eligibility prediction
- Integrate additional financial risk assessment features

---

## 📜 Conclusion

This project demonstrates how Machine Learning can be applied to automate loan approval prediction using historical applicant data.

Accurate loan status prediction can help financial institutions reduce processing time, improve decision-making, and streamline the loan approval process while minimizing risk.
