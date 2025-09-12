# Experiment 3: Email Spam vs. Ham Classification using Machine Learning Models

This experiment aims to build and evaluate different **classification models** for detecting whether an email is **Spam** or **Ham (Not Spam)**.

## Dataset

* Source: [Spambase Dataset (Kaggle)](https://www.kaggle.com/datasets/somesh24/spambase)
* Description: The dataset contains email text features and labels (Spam = 1, Ham = 0).

## Models Implemented

### 1. **Naive Bayes**

* Gaussian Naive Bayes
* Multinomial Naive Bayes

### 2. **Decision Tree & Ensemble Methods**

* Vanilla Decision Tree
* Bagging Classifier
* AdaBoost Classifier
* Gradient Boosting Classifier
* Extreme Gradient Boosting (XGBoost)

### 3. **K-Nearest Neighbors (KNN)**

* KD-Tree based KNN
* Ball-Tree based KNN

### 4. **Support Vector Machine (SVM)**

* Linear Kernel
* Polynomial Kernel
* Radial Basis Function (RBF) Kernel
* Sigmoid Kernel

## Steps Involved

1. Data preprocessing (handling missing values, text feature extraction, scaling if necessary).
2. Train-test split of the dataset.
3. Training classification models.
4. Evaluating models using **Accuracy, Precision, Recall, F1-Score, and ROC-AUC**.
