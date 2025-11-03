# Healthcare Domain: Kidney Disease Classification 
# ![KIdney classification case study](https://www.nanjappahealthcare.com/wp-content/uploads/2025/08/ChronicKidneyDisease_blog-banner-1366x422.png)
## Overview

- Chronic Kidney Disease (CKD) is a serious health condition where the kidneys gradually lose their function over time.
This project aims to classify whether a patient is likely to have **CKD** using various medical indicators and clinical test results.

- By applying machine learning algorithms, this project helps in early disease detection, better diagnosis, and data-driven healthcare insights.

---
## Project Summary

- This project demonstrates an end-to-end ML pipeline to classify kidney disease using structured healthcare data consisting of 400 patient records and 25 features.

## Key Steps

- ### Data Cleaning & EDA:
Performed extensive cleaning, handled missing values and outliers, and analyzed relationships among features.

- ### Feature Processing:
Applied categorical encoding, numerical scaling, and feature engineering for optimal model input.

- ### Model Building:
Implemented multiple classification algorithms — Logistic Regression, Decision Tree, Random Forest, Bagging, AdaBoost, Gradient Boosting, XGBoost, SVM, KNN, Naive Bayes, and Voting Classifier.

- ### Model Comparison:
Compared model performances using accuracy, precision, recall, and F1-score to identify the most robust classifier.

---
## Tech Stack

- Programming Language: Python

- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost, Imbalanced-learn (SMOTE)

- Techniques: Data Cleaning, Feature Encoding, Feature Scaling, Model Evaluation, Cross Validation
---
## Final Model:

Selected Voting Classifier for its stable precision-recall balance.

- Training Accuracy: 0.99375

- Cross Validation Std: 0.01875

- Test Accuracy: 1.0000
