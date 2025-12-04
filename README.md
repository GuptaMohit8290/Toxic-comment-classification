# Toxic-comment-classification
Wikipedia Comments Toxicity Classification Project Overview : The goal of this project is to create a model that predicts the probability of different types of toxicity for comments on Wikipedia. The dataset provided contains comments labeled by human raters for toxic behavior. The types of toxicity are: toxic, severe_toxic, obscene, threat, insult, and identity_hate.

Data The data for this project is provided in four files:

train.csv: contains comments with their binary labels. test.csv: contains comments for which the model will predict the toxicity probabilities. test_labels.csv: labels for the test data. Value of -1 indicates that the comment was not used for scoring. sample_submission.csv: a sample submission file in the correct format. The dataset is released under CC0, and the underlying comment text is governed by Wikipedia's CC-SA-3.0.

To solve this problem, I will create a machine learning model that takes in the text of a comment and predicts the probability of each type of toxicity. We will start by exploring and cleaning the data, followed by feature engineering, and finally, model training and evaluation. We will use various algorithms like Logistic Regression, Naive Bayes, Random Forest, and Neural Networks to achieve the best performance.

Evaluation The model will be evaluated based on its accuracy in predicting the probability of different types of toxicity for each comment. The evaluation metric for this project is the mean column-wise log loss. The model will be ranked based on the mean column-wise log loss.

Conclusion This project will help us understand the classification problem and various machine learning algorithms used to solve it. We will learn how to clean, preprocess and transform the text data for better model performance. Furthermore, we will explore various techniques to handle class imbalance and overfitting. Finally, we will choose the best model based on the evaluation metric and submit our predictions to the competition.
