
# Liver Disease Prediction
This repository contains code and data for predicting liver disease using machine learning algorithms. The goal of this project is to develop a predictive model that can accurately classify individuals as having liver disease or not based on certain features.

## Dataset
The dataset used in this project comprises various health-related attributes of individuals, such as age, gender, total bilirubin, direct bilirubin, alkaline phosphatase, and more. The dataset has been preprocessed to handle missing values and normalized for better model performance.

## Model Selection and Performance
Three different classifiers were explored for this prediction task: 
1. Logistic Regression
2. Support Vector Machine (SVM)
3. Random Forest.

The models were trained and evaluated on the dataset to determine their performance.

Logistic Regression achieved remarkable results, with an accuracy of 98.59%, precision of 98.06%, recall of 100%, and an impressive F-1 score of 99.02% on unscaled data.
SVM's performance was optimized by applying data scaling techniques, resulting in perfect accuracy, precision, recall, and F-1 score on scaled data, while effectively handling 71.13% accuracy and F-1 score on unscaled data.
Random Forest emerged as the top-performing classifier, with outstanding results on scaled data: 99.30% accuracy, 99.02% precision, 100% recall, and a remarkable F-1 score of 99.51%, making it an ideal choice for accurate liver disease prediction.
