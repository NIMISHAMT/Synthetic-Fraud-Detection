**Synthetic Fraud Detection**
This project focuses on detecting fraudulent transactions using a synthetic bank transaction dataset. It involves complete machine learning workflow — from data preprocessing to training multiple classification models and evaluating their performance, especially on imbalanced data.
**Type**: Synthetic data (bank transaction records)
**Target**: Binary classification — Fraud (1) or Not Fraud (0)
**Features include**: Transaction type
                     Old and new balances (origin and destination)
                     Transaction amount
                     Customer and merchant IDs

**Technologies Used**
Python
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn
Imbalanced-learn (for class weight handling)

**Data Preprocessing**
Handled missing values
Encoded categorical variables
Engineered relevant features
Scaled numerical features
Addressed **class imbalance** using class weights in selected models

**Models Implemented**
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Support Vector Machine (SVM)

**Evaluation Metrics**
Accuracy
Confusion Matrix

 **Results Summary**
 **Random Forest** and **SVM** gave the best performance considering both balanced accuracy and recall.
 Models were tuned and evaluated with special attention to the highly **imbalanced nature** of the dataset.

**Project Highlights**
Practical handling of real-world problem: **fraud detection**
Focus on **imbalanced data techniques**
Explained model performance with clear visuals and metrics

