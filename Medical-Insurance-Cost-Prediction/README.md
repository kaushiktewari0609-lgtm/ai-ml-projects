# 🏥 Medical Insurance Cost Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict an individual's medical insurance charges using Machine Learning regression techniques.

The objective is to estimate healthcare insurance costs based on personal and demographic information, helping insurance providers and customers better understand potential medical expenses.

---

## 🎯 Problem Statement

Build a predictive model that estimates medical insurance charges based on various factors such as age, gender, BMI, smoking habits, number of children, and region.

The target variable is:

- **Charges** (Medical Insurance Cost)

---

## 📊 Dataset

The project uses the **Medical Insurance Cost Dataset**.

Target Variable:

- **Charges**

Dataset features include:

- Age
- Sex
- BMI
- Children
- Smoker
- Region
- Charges

### Dataset Usage

The dataset file (`train.csv`) is included in this project repository.

To run the notebook successfully, ensure that the dataset file is located in the same directory as `Medical_Insurance_Cost_Prediction.ipynb`.

If you are using Google Colab, upload the dataset file before executing the notebook.

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
2. Data Loading
3. Data Exploration
4. Data Cleaning
5. Handling Missing Values
6. Exploratory Data Analysis (EDA)
7. Data Encoding
8. Feature Selection
9. Train-Test Split
10. Model Training
11. Model Evaluation
12. Insurance Cost Prediction

---

## 🤖 Machine Learning Model Used

The following regression algorithm was used:

- Linear Regression

### Model Configuration

- Train-Test Split for model evaluation
- R² Score used as the evaluation metric

---

## 📈 Model Performance

The Linear Regression model was trained and evaluated on both training and testing datasets.

Performance was measured using:

- Training R² Score
- Testing R² Score

The model demonstrated good predictive capability for estimating medical insurance charges based on customer information.

---

## 📸 Visualizations

The project includes various visualizations to better understand the dataset and identify factors affecting insurance costs.

Visualizations include:

- Age Distribution
- Gender Distribution
- BMI Distribution
- Children Distribution
- Smoker Distribution
- Region Distribution
- Insurance Charges Distribution

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
Medical_Insurance_Cost_Prediction.ipynb
```

---

## 🎯 Future Improvements

- Implement Random Forest Regressor
- Implement XGBoost Regressor
- Perform hyperparameter tuning
- Compare multiple regression models
- Build an interactive insurance cost prediction web application
- Deploy the model using Streamlit or Flask

---

## 📜 Conclusion

This project demonstrates how Machine Learning can be used to estimate medical insurance costs using customer demographic and lifestyle information.

Accurate insurance cost prediction can help insurance companies improve pricing strategies and assist customers in understanding potential healthcare expenses.
