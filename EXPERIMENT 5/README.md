EXPERIMENT 5 - Classification using KNN and Decision Tree

SCENARIO 1 Breast Cancer Classification (K-Nearest Neighbors)

This scenario implements the K-Nearest Neighbors (KNN) algorithm to classify tumors as malignant or benign using the Breast Cancer dataset. The dataset is loaded and preprocessed by handling missing values and encoding the target variable. Since KNN is distance-based, feature scaling is applied using StandardScaler to ensure fair distance calculation. The data is divided into training and testing sets for model evaluation. Different values of K are tested to determine the optimal number of neighbors. The model’s performance is evaluated using Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix. This scenario demonstrates how distance-based learning works and how model performance varies with different K values.
Dataset Link: https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset

SCENARIO 2 Loan Approval Prediction (Decision Tree Classifier)

This scenario applies a Decision Tree classifier to predict loan approval status based on applicant details. The dataset is loaded and preprocessed by handling missing values and encoding categorical variables. The data is split into training and testing sets to evaluate performance. A Decision Tree model is trained, and its depth is adjusted to study overfitting and underfitting behavior. Predictions are generated for the test data and evaluated using Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix. The tree structure and feature importance are visualized to interpret decision rules. This scenario highlights how rule-based classification works and how model interpretability is an advantage of Decision Trees.
Dataset Link: https://www.kaggle.com/datasets/ninzaami/loan-predication
