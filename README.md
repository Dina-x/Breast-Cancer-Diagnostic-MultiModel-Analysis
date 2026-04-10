# Breast Cancer Diagnostic: Multi-Model Analysis 🧬

## Project Overview
This project provides a comprehensive analysis of the Breast Cancer Wisconsin (Diagnostic) Dataset. It aims to compare various Machine Learning techniques, ranging from traditional probabilistic models to advanced Support Vector Machines and Unsupervised Clustering, to accurately classify tumors as Malignant or Benign.

## Methodology & Implementation

### 1. Supervised Learning (Classification & Optimization)
We implemented and compared several classification algorithms to achieve the highest diagnostic accuracy:
* Support Vector Machine (SVM): Optimized using GridSearchCV for hyperparameter tuning to handle complex data boundaries.
* Logistic Regression & Naive Bayes: Implemented as robust baseline models for probabilistic and linear classification analysis.

### 2. Unsupervised Learning & Dimensionality Reduction
To discover hidden patterns and simplify data dimensions without pre-existing labels:
* K-Means & Hierarchical Clustering: Partitioning the data into groups based on feature similarity to identify natural clusters.
* Principal Component Analysis (PCA): Reducing dimensionality while preserving key variance for effective 2D visualization of tumor clusters.

## Key Technical Skills Applied
* Data Preprocessing: Utilizing StandardScaler to normalize features, ensuring optimal performance for SVM and Clustering algorithms.
* Hyperparameter Tuning: Implementing GridSearchCV to systematically identify the best model configurations.
* Performance Evaluation: Assessing models through Confusion Matrices, Accuracy, Precision, Recall, and F1-Score.
* Data Visualization: Creating Correlation Heatmaps, PCA scatter plots, and Dendrograms using Seaborn and Matplotlib.

## Tech Stack
* Language: Python 
* Libraries: Scikit-learn, Pandas, NumPy, SciPy, Matplotlib, Seaborn.
