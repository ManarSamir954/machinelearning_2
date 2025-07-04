﻿# machinelearning_2
# Breast Cancer Classification 🧬

This project involves diagnosing breast cancer cases using machine learning models, including Support Vector Machine (SVM) and Neural Networks (MLPClassifier). The aim is to accurately differentiate between malignant and benign tumors based on medical measurements.

## 🧪 Dataset

- Breast Cancer Wisconsin (Diagnostic) dataset from `sklearn.datasets`

## 📊 Project Workflow

1. **Data Loading**: From CSV and built-in dataset.
2. **EDA**: Explore class balance and feature distribution.
3. **Outlier Removal**: IQR method to clean data.
4. **Feature Selection**: Based on correlation heatmap.
5. **Model Training**:
   - ✅ SVM Classifier
   - ✅ Neural Network Classifiers (MLP):
     - Simple & Deep Architectures
     - Sigmoid & ReLU activation
     - GridSearchCV for hyperparameter tuning
6. **Evaluation**:
   - Accuracy Score
   - Confusion Matrix
   - ROC-AUC
   - Comparative Bar Chart for NN models

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- GridSearchCV
- MLPClassifier

## 🧠 Goal

To build robust predictive models to assist in early diagnosis of breast cancer, improving accuracy using neural networks and classic classifiers.

