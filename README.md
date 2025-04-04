# Breast_Cancer_Classification

# Breast Cancer Classification using Logistic Regression in PyTorch

This project implements a logistic regression model using PyTorch to classify breast cancer tumors as malignant or benign, based on the popular **Breast Cancer Wisconsin (Diagnostic) dataset**.

---

## 📌 Project Overview

This practice project is part of the Coursera IBM Machine Learning Specialization and covers the full pipeline of building and evaluating a machine learning model in PyTorch.

---

## 🎯 Objectives

- ✅ Load and preprocess the dataset  
- ✅ Build a logistic regression model with PyTorch  
- ✅ Train and evaluate the model  
- ✅ Visualize results using confusion matrix and ROC curve  
- ✅ Save and reload the model  
- ✅ Perform hyperparameter tuning  
- ✅ Analyze feature importance  

---

## 📂 Dataset

The dataset contains 569 samples with 30 numerical features extracted from digitized images of breast mass tissue.

- Target column: `diagnosis`  
  - `M` = Malignant (1)  
  - `B` = Benign (0)  

You can find the dataset [here](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) if not already provided.

---

## 🛠️ Dependencies

Install required Python packages:

```bash
pip install torch scikit-learn pandas matplotlib numpy
