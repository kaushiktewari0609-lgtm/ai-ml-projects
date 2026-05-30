# 🛒 Big Mart Sales Prediction

## 📌 Project Overview

This project aims to predict product sales at Big Mart outlets using Machine Learning regression models.

The objective is to help retail businesses improve inventory planning, demand forecasting, and decision-making through data-driven insights.

---

## 🎯 Problem Statement

Build a predictive model that estimates **Item_Outlet_Sales** using product and outlet-related features such as:

- Item Type
- Item Weight
- Item Visibility
- Item MRP
- Outlet Size
- Outlet Location Type
- Outlet Type

---

## 📊 Dataset

The project uses the Big Mart Sales dataset.

Target Variable:

- **Item_Outlet_Sales**

Dataset features include:

- Item_Identifier
- Item_Weight
- Item_Fat_Content
- Item_Visibility
- Item_Type
- Item_MRP
- Outlet_Identifier
- Outlet_Size
- Outlet_Location_Type
- Outlet_Type

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow

1. Data Collection
2. Data Cleaning
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Data Preprocessing
7. Model Building
8. Model Evaluation

---

## 📈 Model Performance

Different regression models were trained and evaluated.

- Linear Regression
- Random Forest Regressor

Random Forest Regressor achieved better prediction performance compared to Linear Regression.

---

## 📸 Visualizations

The project includes various visualizations such as:

- Item Weight Distribution
- Item Visibility Distribution
- Item MRP Distribution
- Outlet Analysis
- Feature Relationship Analysis

Screenshots are available in the **images/** folder.

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
Big_Mart_Sales_Prediction.ipynb
```

---

## 🎯 Future Improvements

- Implement XGBoost for improved performance
- Perform hyperparameter tuning
- Build an interactive prediction interface
- Deploy the model using Streamlit or Flask
- Integrate real-time sales data

---

## 📜 Conclusion

This project demonstrates how Machine Learning can be applied to predict retail sales using historical data.

Accurate sales prediction can help businesses optimize inventory management, improve operational efficiency, and make better strategic decisions.
