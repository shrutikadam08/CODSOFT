## Credit Card Fraud Detection


# Overview
This project aims to detect fraudulent credit card transactions using Machine Learning algorithms. Given a dataset of transactions, we classify them as fraudulent or legitimate by applying various ML techniques. This helps in preventing financial fraud and securing digital transactions.

# Dataset
The dataset consists of real or synthetic credit card transactions, typically including:
 1.Transaction Amount
 2.Time of Transaction
 3.Anonymized Features (V1, V2, ..., V28)
 4.Class Label (0 = Legitimate, 1 = Fraudulent)
 
# Technologies Used
🔹 Python 🐍
🔹 Pandas & NumPy (Data Manipulation)
🔹 Matplotlib & Seaborn (Data Visualization)
🔹 Scikit-Learn (Machine Learning Models)

# Implementation Steps
1️⃣ Data Preprocessing: 
Handling missing values, scaling, and encoding categorical data.
Addressing class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

2️⃣ Exploratory Data Analysis (EDA):
Understanding fraud patterns using graphs & correlation heatmaps.

3️⃣ Model Selection & Training:
Implementing and comparing:
   ✅ Logistic Regression
   ✅ Decision Trees
   ✅ Random Forest
   
4️⃣ Model Evaluation:
Using Accuracy, Precision, Recall, F1-Score, and ROC-AUC to measure performance.

5️⃣ Prediction & Fraud Detection:
Deploying the model to classify transactions.

 # Results & Findings
Random Forest provided the best fraud detection accuracy.
Feature engineering & balancing techniques significantly improved performance.
Data imbalance was a major challenge, tackled using oversampling techniques.


