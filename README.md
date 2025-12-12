# Breast Cancer Diagnosis Prediction using KNN and K-Means

## Overview
This project implements machine learning techniques to classify breast cancer cases as malignant or benign. The analysis is performed using K-Means clustering for unsupervised pattern observation and K-Nearest Neighbors for supervised classification.

## Dataset
The Breast Cancer dataset consists of numerical features computed from cell nuclei characteristics.
The diagnosis column is encoded as:
Malignant as 1  
Benign as 0  

The id and Unnamed: 32 columns are removed during preprocessing.

## Preprocessing Steps
Diagnosis values are encoded numerically.
Min-Max normalization is applied to scale all features between 0 and 1.
The dataset is split into 80 percent training data and 20 percent testing data.

## Algorithms Implemented
K-Means clustering with k equal to 2 is used to observe natural grouping of benign and malignant cases.
K-Nearest Neighbors classifier with k equal to 5 is trained on the training dataset.

## Evaluation Metrics
Model performance is evaluated using:
Accuracy  
Precision  
Recall  
F1 Score  

## Results
Accuracy 96.49 percent  
Precision 95.35 percent  
Recall 95.35 percent  
F1 Score 95.35 percent  

## Files in This Repository
breastCancerKNN.ipynb contains all preprocessing, model training, and evaluation code.  
dataset.csv contains the Breast Cancer dataset used in this project.

## Tools and Libraries
Python  
Google Colab  
Pandas  
NumPy  
Scikit-learn  
