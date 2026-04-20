# K-Nearest Neighbors (KNN) Assignment
## ARTI 308: Machine Learning - Lab 8 Assignment

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### Assignment Overview
This repository contains a K-Nearest Neighbors (KNN) implementation to predict a target class based on hidden feature data. The Assignment emphasizes the importance of feature scaling when working with distance-based algorithms.

### 🚀 Workflow & Tasks Completed
1. **Data Standardization:** Used `StandardScaler` to scale features, ensuring that variables with larger magnitudes do not dominate the Euclidean distance calculations.
2. **Train/Test Split:** Divided the dataset using a 70/30 split.
3. **Model Training (K=1):** Built an initial KNN model with K=1 and evaluated its performance.
4. **The Elbow Method:** Iterated through K values from 1 to 40, recording the error rate for each to find the optimal K value visually.
5. **Model Optimization (K=30):** Retrained the model using the optimal value (K=30), which improved the overall model performance and reduced noise sensitivity.

### 📂 Files in this Repository
* `02-K Nearest Neighbors Assignment.ipynb`: The main notebook containing the EDA, Elbow Method plot, and evaluation metrics.
* `KNN_Project_Data`: The anonymized dataset used for model training.
