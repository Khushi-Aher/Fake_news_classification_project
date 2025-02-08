# Fake News Detection using Ensemble Machine Learning Models

This project focuses on detecting fake news using an ensemble of machine learning models, including XGBoost, Random Forest, and Logistic Regression. The pipeline covers data preprocessing, feature engineering, text vectorization, dimensionality reduction, model training with hyperparameter tuning, and performance evaluation.


# 🚀 Features
* Data Preprocessing:  Text cleaning, lemmatization, and removal of stopwords.
* Feature Engineering:  Sentiment analysis, word density, and text length analysis.
* Text Vectorization:  TF-IDF with unigrams and bigrams.
* Dimensionality Reduction:  Using Truncated SVD for efficient model performance.
* Class Imbalance Handling:  SMOTE oversampling to balance datasets.
* Model Ensemble:  Combining XGBoost, Random Forest, and Logistic Regression with soft voting.
* Performance Metrics:  Accuracy, Precision, Recall, F1 Score, AUC-ROC, and Confusion Matrix visualization.
* Feature Importance:  Identifying significant features contributing to predictions.


# 📂 Dataset
* Input: The dataset contains news articles with fields like title, text, and label (0 for fake, 1 for real).
* Files:
 1. train.csv: Training dataset.
 2. test.csv: Test dataset.


# 📊 Model Performance
After training and evaluation, the following metrics are computed:

- Accuracy: Measures the overall correctness.

![image](https://github.com/user-attachments/assets/9b165940-48de-4c7f-9453-34817957bed9)




- AUC-ROC: Shows how well the model distinguishes between classes
  
 ![image](https://github.com/user-attachments/assets/d3f8204f-411b-4b54-a7e2-fe5f4b40a40a)




- Precision: Indicates the percentage of correctly identified fake news out of all predicted fake news.
- Recall: Measures the ability to find all actual fake news.
- F1 Score: Harmonic mean of precision and recall.
