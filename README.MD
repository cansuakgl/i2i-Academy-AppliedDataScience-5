## Bike Buyers Classification (KNN vs XGBoost)

A simple machine learning notebook that compares K-Nearest Neighbors (KNN) and XGBoost on the Bike Buyers dataset.

### Demo

<p align="center">
  <img src="docs\Kayıt 2026-07-02 165606.gif" alt="Project Demo" width="700">
</p>

### Features

- Loads and explores the Bike Buyers dataset
- Performs basic exploratory data analysis (EDA)
- Preprocesses numerical and categorical features
  - Missing value imputation
  - Feature scaling (KNN)
  - One-hot encoding
- Trains and evaluates:
  - K-Nearest Neighbors (KNN)
  - XGBoost
- Displays:
  - Classification reports
  - Confusion matrices
  - Accuracy, Precision, Recall, and F1-score comparison

### Dataset

The dataset is the **Bike Buyers** dataset from Kaggle:

https://www.kaggle.com/datasets/heeraldedhia/bike-buyers


### Results

The notebook compares both models using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

For this dataset, both models achieved similar performance, with KNN obtaining a slightly higher Recall and F1-score.