# 📞 Customer Churn Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict customer churn using Machine Learning classification models.

The objective is to help businesses identify customers who are likely to discontinue their services, enabling proactive customer retention strategies and improved business decision-making.

---

## 🎯 Problem Statement

Build a predictive model that determines whether a customer is likely to **Churn** or **Not Churn** based on customer demographics, account information, and service usage patterns.

The target variable is:

- **Churn**

---

## 📊 Dataset

The project uses the **Telco Customer Churn Dataset**.

### Target Variable

- **Churn**
  - Yes → Customer leaves the service
  - No → Customer stays with the service

### Dataset Features

The dataset includes customer-related information such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract Type
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges

### Dataset Usage

The dataset file (`train.csv`) is included in this project repository.

To run the notebook successfully, ensure that `train.csv` is located in the same directory as `Customer_Churn_Prediction_using_ML.ipynb`.

If you are using Google Colab, upload the dataset file before executing the notebook.

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Jupyter Notebook

---

## 🔍 Project Workflow

1. Data Collection
2. Data Cleaning
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Feature Encoding
6. Feature Engineering
7. Data Preprocessing
8. Train-Test Split
9. Class Balancing using SMOTE
10. Model Training
11. Model Evaluation
12. Model Saving and Prediction

---

## 🤖 Machine Learning Models Used

The following classification models were trained and evaluated:

- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

### Cross Validation

- 5-Fold Cross Validation was performed for model comparison.

### Handling Imbalanced Data

- SMOTE (Synthetic Minority Over-sampling Technique) was used to balance the target classes before model training.

---

## 📈 Model Performance

Different classification models were trained and compared using cross-validation accuracy.

The **Random Forest Classifier** was selected as the final model and evaluated on the test dataset using:

- Accuracy Score
- Confusion Matrix
- Classification Report

The trained model was then saved using Pickle for future predictions.

---

## 📸 Visualizations

The project includes various visualizations such as:

- Customer Churn Distribution
- Numerical Feature Distributions
- Service Usage Analysis
- Correlation Analysis
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
Customer_Churn_Prediction_using_ML.ipynb
```

---

## 🎯 Future Improvements

- Perform hyperparameter tuning
- Implement advanced ensemble techniques
- Deploy the model using Streamlit or Flask
- Build a real-time churn prediction dashboard
- Integrate live customer data sources
- Improve model interpretability using SHAP or LIME

---

## 📜 Conclusion

This project demonstrates how Machine Learning can be applied to predict customer churn using historical customer data.

Accurate churn prediction can help organizations improve customer retention, reduce revenue loss, and make data-driven business decisions through proactive intervention strategies.
