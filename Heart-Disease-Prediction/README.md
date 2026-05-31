# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict the presence of heart disease using Machine Learning classification techniques.

The objective is to assist in early detection of cardiovascular diseases by analyzing patient health parameters and generating accurate predictions based on medical data.

---

## 🎯 Problem Statement

Build a predictive model that determines whether a patient is likely to have **Heart Disease** based on various medical attributes.

The target variable is:

- **Target**
  - 0 → No Heart Disease
  - 1 → Heart Disease Present

---

## 📊 Dataset

The project uses the **Heart Disease Dataset** containing medical information of patients.

### Dataset Features

The dataset includes various health-related attributes such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting Electrocardiographic Results
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- ST Depression
- Slope of Peak Exercise ST Segment
- Number of Major Vessels
- Thalassemia

### Target Variable

- Target

### Dataset Usage

The dataset file (`train.csv`) is included in this project repository.

To run the notebook successfully, ensure that `train.csv` is located in the same directory as `Heart_Disease_Prediction.ipynb`.

If you are using Google Colab, upload the dataset file before executing the notebook.

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow

1. Data Collection
2. Data Loading
3. Data Exploration
4. Data Preprocessing
5. Feature and Target Separation
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Prediction System Development

---

## 🤖 Machine Learning Model Used

The following classification algorithm was used:

- Logistic Regression

### Data Preprocessing

- Feature selection and data preparation
- Train-Test Split for model evaluation

---

## 📈 Model Performance

The Logistic Regression model was trained and evaluated using:

- Training Accuracy
- Testing Accuracy

The model demonstrated good performance in predicting the presence of heart disease based on patient health parameters.

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
Heart_Disease_Prediction.ipynb
```

---

## 🎯 Future Improvements

- Experiment with advanced classification algorithms
- Perform hyperparameter tuning
- Apply feature engineering techniques
- Build a web-based prediction system using Streamlit
- Deploy the model for real-time predictions
- Integrate electronic health record data

---

## 📜 Conclusion

This project demonstrates how Machine Learning can be applied to healthcare problems for heart disease prediction.

By analyzing patient medical data, the model can help identify individuals at risk of heart disease, supporting early diagnosis and informed clinical decision-making.
