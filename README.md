# Breast Cancer Diagnostic: Multi-Model Analysis 🧬

## Project Overview
This project provides a comprehensive analysis of the **Breast Cancer Wisconsin (Diagnostic) Dataset**. It aims to compare various Machine Learning techniques, ranging from traditional linear models to advanced Support Vector Machines and Unsupervised Clustering, to accurately classify tumors as Malignant or Benign.

## Implementation Details

### Part 1: Supervised Learning (Classification)
We implemented and compared several classification algorithms to achieve the highest diagnostic accuracy:
* **Linear Models:** Logistic Regression.
* **Probabilistic Models:** Gaussian Naive Bayes.

### Part 2: Unsupervised Learning (Clustering & PCA)
To discover hidden patterns and simplify data dimensions, we applied:
* **K-Means Clustering:** Grouping data points based on feature similarity.
* **Hierarchical Clustering:** Building a dendrogram to visualize data relationships.
* **Advanced Models:** Support Vector Machine (SVM) with Hyperparameter Tuning using GridSearchCV.
* **Principal Component Analysis (PCA):** Reducing dimensionality while preserving the most important variance in the dataset.

## Key Features
* **Data Visualization:** Using Seaborn and Matplotlib for Correlation Matrices and Confusion Matrices.
* **Performance Metrics:** Evaluation based on Accuracy, Precision, Recall, and F1-Score.
* **Optimization:** Used StandardScaler for feature scaling and GridSearchCV for model optimization.

## Tech Stack
* **Language:** Python 
* **Libraries:** Pandas, NumPy, Scikit-learn, Scipy, Matplotlib, Seaborn.
