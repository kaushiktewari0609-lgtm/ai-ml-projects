# 🩺 Breast Cancer Classification Using Neural Network

## 📌 Project Overview

This project aims to classify breast cancer tumors as **Benign** or **Malignant** using a **Neural Network (NN)** built with TensorFlow and Keras.

The objective is to assist in early cancer detection by leveraging Machine Learning techniques to analyze medical diagnostic data and provide accurate predictions.

---

## 🎯 Problem Statement

Build a classification model that predicts whether a breast tumor is:

- **Benign (Non-Cancerous)**
- **Malignant (Cancerous)**

using various diagnostic features extracted from breast cancer diagnostic data.

---

## 📊 Dataset

The project uses the **Breast Cancer Wisconsin Diagnostic Dataset** available through Scikit-learn.

### Target Variable

- **Diagnosis Label**

### Class Labels

- **0 → Malignant**
- **1 → Benign**

### Dataset Features

The dataset contains 30 numerical features, including:

- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Smoothness
- Mean Compactness
- Mean Concavity
- Mean Symmetry
- Radius Error
- Texture Error
- Perimeter Error
- Area Error
- Worst Radius
- Worst Texture
- Worst Perimeter
- Worst Area

and other diagnostic measurements.

### Dataset Usage

The dataset is loaded directly from Scikit-learn:

```python
from sklearn.datasets import load_breast_cancer

data = load_breast_cancer()
```

No external CSV file is required.

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras
- Jupyter Notebook

---

## 🔍 Project Workflow

1. Data Collection
2. Data Loading
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Feature Scaling
6. Train-Test Split
7. Neural Network Model Building
8. Model Training
9. Model Evaluation
10. Prediction and Classification

---

## 🧠 Neural Network Architecture

The model consists of:

- Input Layer (30 Features)
- Dense Hidden Layer (ReLU Activation)
- Output Layer (Sigmoid Activation)

### Optimizer

- Adam

### Loss Function

- Sparse Categorical Crossentropy

### Evaluation Metric

- Accuracy

---

## 📈 Model Performance

The Neural Network was trained and evaluated on the dataset.

Performance metrics include:

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Training Loss
- Validation Loss

The model achieved high accuracy in distinguishing between benign and malignant tumors.

---

## 📸 Visualizations

The project includes various visualizations such as:

- Training Accuracy vs Validation Accuracy
- Training Loss vs Validation Loss
- Dataset Feature Analysis
- Class Distribution Analysis

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
Breast_Cancer_Classification_with_Neural_Network.ipynb
```

---

## 🎯 Future Improvements

- Add more hidden layers for deeper learning
- Perform hyperparameter tuning
- Implement Dropout for regularization
- Compare with other classification algorithms
- Deploy the model using Streamlit or Flask
- Integrate real-time medical diagnostic inputs

---

## 📜 Conclusion

This project demonstrates how Neural Networks can be applied to medical diagnosis problems for breast cancer classification.

Accurate classification of tumors as benign or malignant can assist healthcare professionals in making informed decisions and support early detection, leading to better patient outcomes.
