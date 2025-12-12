Breast Cancer Diagnosis Prediction using KNN and K-Means

Objective
The objective of this assignment is to classify breast cancer cases as malignant or benign using machine learning techniques. K-Means clustering is used to observe natural grouping of data, and K-Nearest Neighbors is used as a supervised classifier.

Dataset
The Breast Cancer dataset contains multiple numerical features extracted from cell nuclei. The diagnosis column is encoded as malignant (1) and benign (0). The id and Unnamed: 32 columns are removed during preprocessing.

Preprocessing
The diagnosis column is encoded where M is converted to 1 and B is converted to 0. Min-Max normalization is applied to all feature values to scale them between 0 and 1. The dataset is split into 80 percent training data and 20 percent testing data.

Algorithms Used
K-Means clustering with k equal to 2 is applied to observe clustering patterns between benign and malignant cases.  
K-Nearest Neighbors classifier with k equal to 5 is trained on the training data.

Evaluation Metrics
The model is evaluated using accuracy, precision, recall, and F1 score.

Results
Accuracy 96.49 percent  
Precision 95.35 percent  
Recall 95.35 percent  
F1 Score 95.35 percent  

These results indicate that the KNN model performs well in predicting breast cancer diagnosis.

Tools and Libraries
Python  
Google Colab  
Pandas  
NumPy  
Scikit-learn  

Repository Structure
Breast_Cancer_KNN_KMeans.ipynb  
Dataset.csv  
README.md  
