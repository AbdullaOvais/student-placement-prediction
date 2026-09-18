# Student Placement Prediction using Logistic Regression

A machine learning project that predicts whether a student is likely to be placed based on their **CGPA** and **IQ** using **Logistic Regression**.

## 📌 Project Overview

The objective of this project is to build a simple binary classification model that predicts student placement outcomes using academic and aptitude-related features.

The project follows a basic machine learning pipeline:

- Data loading and exploration
- Data preprocessing
- Feature and target extraction
- Train-test split
- Feature scaling
- Logistic Regression model training
- Model evaluation
- Decision boundary visualization
- Model serialization using Pickle

---

## 🎯 Objective

To develop a machine learning model that predicts whether a student will be placed based on:

- **CGPA**
- **IQ**

### Target Variable

- `0` → Not Placed
- `1` → Placed

---

## 📊 Dataset

The project uses a student placement dataset containing information related to:

| Feature | Description |
|---------|-------------|
| CGPA | Student's academic performance |
| IQ | Intelligence Quotient score |
| Placement | Placement outcome |

The first column in the original dataset is removed during preprocessing as it represents an unnecessary index column.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Mlxtend
- Pickle
- Jupyter Notebook

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Logistic Regression
   ↓
Prediction
   ↓
Accuracy Evaluation
   ↓
Decision Boundary Visualization
   ↓
Model Serialization
