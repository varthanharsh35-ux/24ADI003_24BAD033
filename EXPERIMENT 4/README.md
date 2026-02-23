EXPERIMENT 4 : Probabilistic Classification using Naive Bayes

SCENARIO 1 : SMS Spam Classification (Multinomial Naïve Bayes)

This scenario implements Multinomial Naïve Bayes to classify SMS messages as Spam or Ham. The dataset is loaded and basic preprocessing such as converting text to lowercase and removing special characters is performed. The text data is converted into numerical format using TF-IDF vectorization. The target labels are encoded and the dataset is split into training and testing sets. The model is trained using the training data and predictions are generated for the test set. Performance is evaluated using Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix. This scenario demonstrates how probabilistic classification works effectively for text-based datasets using word frequency patterns.


SCENARIO 2 : Iris Flower Classification (Gaussian Naïve Bayes)

This scenario applies Gaussian Naïve Bayes to classify iris flowers into three species based on numerical features. The dataset is loaded and feature scaling is applied to normalize the values. The data is split into training and testing sets for evaluation. The Gaussian Naïve Bayes model is trained on the training data and tested on unseen samples. Performance metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrix are calculated. Class probabilities are analyzed to understand prediction confidence. This scenario shows how Naïve Bayes handles continuous numerical features using Gaussian probability distribution.
