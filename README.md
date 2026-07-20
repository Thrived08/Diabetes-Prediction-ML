# Diabetes Prediction Using Machine Learning

## Project Overview

This project uses Machine Learning classification algorithms to predict whether a person is diabetic or non-diabetic based on medical information.

The goal of this project is to build a model that can assist in early diabetes prediction using patient health parameters.

---

## Problem Statement

Diabetes is a common health condition that requires early detection. Machine learning can help analyze medical data and predict the possibility of diabetes based on important health factors.

---

## Dataset

The dataset contains medical records with different health-related features.

### Input Features

- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target Variable

**Outcome**

- 0 → Non-Diabetic
- 1 → Diabetic

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Workflow

The project follows these steps:

1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Feature Scaling
7. Model Training
8. Model Evaluation

---

## Data Preprocessing

The following preprocessing techniques were applied:

- Handling missing values
- Feature engineering using derived attributes:
  - BMI Categories
  - Insulin Categories
- Encoding categorical features using One-Hot Encoding
- Feature scaling using StandardScaler

---

## Machine Learning Models Used

The following classification algorithms were implemented:

- Logistic Regression
- Naive Bayes Classifier

---

## Model Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# Results

## Logistic Regression Performance

| Metric | Score |
|--------|-------|
| Accuracy | 89.61% |
| Precision | 81.63% |
| Recall | 85.10% |
| F1 Score | 83.33% |

---

## Naive Bayes Performance

| Metric | Score |
|--------|-------|
| Accuracy | 88.31% |
| Precision | 77.00% |
| Recall | 87.00% |
| F1 Score | 82.00% |

### Detailed Classification Report
