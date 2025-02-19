## SMS Spam Classification

# Overview
This project implements an SMS spam classification model using three different machine learning algorithms:
   Naive Bayes
   Logistic Regression
   Support Vector Machine (SVM)
It utilizes TF-IDF (Term Frequency-Inverse Document Frequency) for text feature extraction and compares the models based on performance metrics such as accuracy, precision, recall, and ROC curves.

# Dataset
The dataset consists of SMS messages labeled as either spam or ham (legitimate). The dataset is preprocessed to remove unwanted characters and stop words before training the models.

# Models Implemented
1. Naive Bayes - Uses the probabilistic approach for classification.
2. Logistic Regression - A linear model for binary classification.
3. Support Vector Machine (SVM) - Uses hyperplanes to classify messages.
The models are evaluated based on:
    Accuracy
    Precision
    Recall
    F1-Score
    ROC-AUC Curve

# Visualizations
This project includes various visualizations:
Confusion Matrix: Model performance comparison
AUC-ROC Curve: Evaluates model effectiveness
Bar Graphs: Comparison of accuracy, precision, and recall

