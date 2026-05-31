# 🩺 Diabetes Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict whether a person is diabetic or non-diabetic using Machine Learning techniques.

The objective is to develop a predictive system that analyzes various medical attributes and determines the likelihood of diabetes, helping support early diagnosis and healthcare decision-making.

---

## 🎯 Problem Statement

Build a Machine Learning model that predicts whether a person has diabetes based on medical diagnostic measurements.

The target variable is:

- **Outcome**
  - 0 → Non-Diabetic
  - 1 → Diabetic

---

## 📊 Dataset

The project uses the **Pima Indians Diabetes Dataset**.

### Dataset Features

The dataset contains the following medical attributes:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age

### Target Variable

- Outcome

### Dataset Usage

The dataset file (`train.csv`) is included in this project repository.

To run the notebook successfully, ensure that `train.csv` is located in the same directory as `Diabetes_Prediction.ipynb`.

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
7. Data Standardization
8. Model Training
9. Model Evaluation
10. Prediction System Development

---

## 🤖 Machine Learning Model

The project uses:

- Support Vector Machine (SVM)

### Model Configuration

- Kernel: Linear
- Feature Scaling: StandardScaler

---

## 📈 Model Performance

The model was trained using the training dataset and evaluated on unseen test data.

Evaluation metrics include:

- Training Accuracy
- Testing Accuracy

The trained model demonstrated good performance in predicting whether a patient is diabetic or non-diabetic based on the provided health parameters.

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
Diabetes_Prediction.ipynb
```

---

## 🎯 Future Improvements

- Experiment with additional classification algorithms
- Perform hyperparameter tuning
- Implement ensemble learning techniques
- Build a web-based prediction interface using Streamlit
- Deploy the model for real-time predictions

---

## 📜 Conclusion

This project demonstrates how Machine Learning can be applied to healthcare problems for diabetes prediction.

By analyzing patient health data, the model can assist in identifying individuals at risk of diabetes, supporting early diagnosis and informed medical decision-making.
