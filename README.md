# Fraud Transaction Customer Segmentation & Classification
## Overview

This project implements an end-to-end Machine Learning workflow by combining Unsupervised Learning and Supervised Learning techniques on a financial transaction dataset.

The objective is to:

Discover hidden customer transaction patterns using K-Means Clustering.
Generate cluster labels as pseudo-targets.
Build classification models capable of predicting cluster membership.
Compare multiple classification approaches and perform hyperparameter tuning.

This project was developed as part of the Machine Learning learning pathway and demonstrates practical implementation of clustering, dimensionality reduction, classification, and model evaluation.

---
## Dataset
The dataset contains transaction-related information, customer demographics, and financial activity patterns.

Key characteristics:
- 2,500+ transaction records
- Numerical and categorical features
- Customer behavior attributes
- Transaction activity indicators

Potential use cases:
- Customer segmentation
- Behavioral analysis
- Fraud pattern exploration
- Risk profiling
---
## Project Workflow
### 1. Exploratory Data Analysis (EDA)
Performed initial data exploration:
- Dataset inspection
- Descriptive statistics
- Missing value analysis
- Duplicate detection
- Correlation analysis
- Feature distribution visualization
### 2. Data Preprocessing
Several preprocessing steps were applied:
- Missing value removal
- Duplicate removal
- Feature encoding using LabelEncoder
- Outlier handling
- Feature scaling using StandardScaler
- Feature engineering and binning
### 3. Clustering
Implemented:
- K-Means Clustering
- Elbow Method for optimal cluster selection
- Silhouette Score evaluation
- Cluster visualization
- PCA-based clustering comparison

Generated output:
`model_clustering.h5
PCA_model_clustering.h5`
### 5. Classification
Built classification models to predict cluster labels.

Models explored:
- Decision Tree Classifier
- Additional classification model comparison
- Hyperparameter tuning

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-Score

Generated models:
`decision_tree_model.h5
explore_Umar_Shidiq_Ibadurrohman_classification.h5
tuning_classification.h5`

---
## Project Structure
.
├── data_clustering.csv
├── data_clustering_inverse.csv
├── model_clustering.h5
├── PCA_model_clustering.h5
├── decision_tree_model.h5
├── explore_Umar_Shidiq_Ibadurrohman_classification.h5
├── tuning_classification.h5
├── [Clustering]_Submission_Akhir_BMLP_Umar_Shidiq_Ibadurrohman.ipynb
└── [Klasifikasi]_Submission_Akhir_BMLP_Umar_Shidiq_Ibadurrohman.ipynb

---
## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Yellowbrick
- Joblib
---

## Key Learning Outcomes
Through this project, I gained hands-on experience in:
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Customer Segmentation
- K-Means Clustering
- PCA Dimensionality Reduction
- Cluster Interpretation
- Classification Modeling
- Hyperparameter Optimization
- Machine Learning Model Deployment Preparation

---
##Results
The project successfully demonstrates how clustering can be used to generate meaningful labels from unlabeled data and how those labels can subsequently be leveraged to train supervised machine learning models for future prediction tasks.

---

Author
Umar Shidiq Ibadurrohman
Physics Undergraduate | Data Science & Machine Learning Enthusiast
