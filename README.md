## Dataset Overview:
It is crucial for credit card companies to detect fraudulent transactions to protect customers from unauthorized purchases. This project uses the Credit Card Fraud Detection Dataset from Kaggle.
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud 
## Dataset Content
**Time Period**: made in September 2013 by European cardholders.

**Size** : The dataset contains 284,807 transactions over two days.

**Fraud Instances**:  Total fraudulent transactions: 492.

Fraud transactions account for 0.172% of all transactions, making the dataset highly imbalanced.
## Features
**PCA Features**: 

The dataset includes 28 principal components labeled as V1, V2, ..., V28.

**Non-PCA Features**:

**Time**:  Seconds elapsed since the first transaction.

**Amount**:  The transaction amount (useful for cost-sensitive learning).

**Target**:

**Class**:  Binary response variable.

0 → Non-fraudulent transaction.

1 → Fraudulent transaction.
## Project: 
Fraud Detection Using Machine Learning
This project focuses on fraud detection using machine learning techniques, with an emphasis on the Naive Bayes Classifier and comparisons with other models.
## Models Used
Naive Bayes Classifier
Support Vector Machines (SVM)
Random Forest Classifier
Logistic Regression
K-Nearest Neighbors (KNN)
## Objectives
Compare the performance of the Naive Bayes Classifier against other machine learning models.
Handle the class imbalance using appropriate strategies such as resampling, class weighting, or ensemble methods.
## Measure performance using meaningful metrics:
Precision , 
Recall ,
F1 Score
## Result:
I prefer NB After_Drop PCs + Time + ScaledAmount over models using SMOTE (like LR_with_SMOTE) is very reasonable for real-world deployment scenarios. It provides a good balance of recall for both classes while ensuring reliability and robustness without relying on synthetic data. high recall for Class 1 (0.87) , strong performance for Class 0 (0.98)
## How to Run the Project
Prerequisites
Install required libraries:
pip install pandas numpy scikit-learn matplotlib seaborn
## Clone the Repository:
https://github.com/TasneimAhmed/Credit-Card-Fraud-Detection.git 
