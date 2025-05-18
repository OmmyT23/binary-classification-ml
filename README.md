# Binary Classification with PCA and Supervised Models

This project was developed as part of a university assignment at Sapienza University of Rome.  
The goal was to classify binary-labeled data using various supervised learning techniques and dimensionality reduction.

## 📌 Objectives

- Explore and visualize the dataset
- Clean data and detect outliers
- Apply Principal Component Analysis (PCA)
- Train and evaluate multiple classifiers
- Compare performance using ROC-AUC and cross-validation

## 🛠 Tools & Libraries

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 📊 Dataset

A synthetic dataset with 6 continuous features and a binary target variable (`0` or `1`).

## 🔍 Project Workflow

1. **Exploratory Data Analysis:**  
   Visualized feature distributions using histograms and scatter matrices.

2. **Outlier Detection & Cleaning:**  
   Removed anomalies to improve model generalization.

3. **Dimensionality Reduction:**  
   Applied PCA to project data into a lower-dimensional space while retaining variance.

4. **Model Training:**  
   - Gaussian Naive Bayes  
   - k-Nearest Neighbors  
   - Random Forest  
   - Linear Discriminant Analysis (LDA)

5. **Performance Evaluation:**  
   - Confusion Matrix  
   - Cross-Validation Accuracy  
   - ROC Curve and AUC Score

## ✅ Results

The Random Forest and LDA models performed best, achieving high accuracy and AUC scores.  
PCA helped reduce feature complexity without significant performance loss.

---

📁 The full code is available in the notebook:  
`Binary_Classification_Model.ipynb`

