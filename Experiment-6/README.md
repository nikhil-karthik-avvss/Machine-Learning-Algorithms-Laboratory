# Experiment 6: Principal Component Analysis (PCA)

This experiment applies **Principal Component Analysis (PCA)** as a **feature selection / dimensionality reduction** technique and evaluates the performance of various classifiers on the reduced feature space.

## Objective

To investigate how **PCA-transformed features** affect the performance of different machine learning classifiers in the task of **email spam vs. ham classification**.

## Dataset

* Source: \[Spambase Dataset (UCI / Kaggle)]
* Description: The dataset contains extracted features from emails labeled as **Spam (1)** or **Ham (0)**.

## Models Implemented

The following classifiers are trained on PCA-transformed features:

1. **Support Vector Machine (SVM – Linear Kernel)**
2. **Naïve Bayes**

   * Gaussian Naïve Bayes
   * Multinomial Naïve Bayes
3. **k-Nearest Neighbors (KNN)**
4. **Logistic Regression**
5. **Decision Tree Classifier**
6. **Random Forest Classifier**
7. **AdaBoost Classifier**
8. **Gradient Boosting Classifier**
9. **Extreme Gradient Boosting (XGBoost)**
10. **Stacking Classifier**

* Base learners: mix of the above classifiers
* Meta-learner: higher-level classifier to combine base outputs

## Steps Involved

1. Preprocess dataset (handling missing values, scaling).
2. Apply **PCA** for dimensionality reduction.
3. Train models on reduced features.
4. Evaluate performance using **Accuracy, Precision, Recall, F1-Score, and ROC-AUC**.
5. Compare results with and without PCA to assess its effectiveness.
