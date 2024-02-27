# Credit-Card-Fraud-Detection
Overview
Credit card fraud is a significant issue affecting both companies and customers. Machine learning algorithms have become a common tool for detecting fraudulent transactions. However, the datasets used for this task are often highly imbalanced, with a small proportion of fraudulent transactions. This project aimed to address this challenge by investigating balancing strategies on highly imbalanced datasets and developing a generic classifier selection technique to build appropriate models from any imbalanced dataset without prior information. Additionally, the project aimed to identify the most important predictor variables influencing the classification of a transaction as fraud or non-fraud.

Methodology
Dataset: Used a highly imbalanced credit card fraud dataset.
Balancing Strategy: Applied random undersampling to balance the data.
Classification Algorithms: Fitted four classification algorithms to the dataset: Logistic Regression, K Nearest Neighbors, Support Vector Classifier, and Decision Tree Classifier.
Evaluation: Evaluated the performance of the algorithms and identified the most important predictor variables using permutation importance.
Results
Random undersampling effectively balanced the dataset, improving the performance of classification algorithms.
Logistic Regression and Support Vector Classifier performed best, with Support Vector Classifier being the best-performing model overall.
Permutation importance identified V14 as the most important predictor variable, followed by V17.
Interpretation
Random undersampling is effective for balancing highly imbalanced datasets, improving the performance of classification algorithms.
Logistic regression shows promise as a generic classifier selection technique.
V14 and V17 are the most important predictor variables for classifying transactions as fraud or non-fraud.
Implications
The findings can inform the development of more accurate fraud detection models for credit card companies.
Financial institutions can use the significant predictor variables to develop tailored fraud detection algorithms.
The best-performing algorithm (SVC) can effectively detect fraud in credit card transactions, helping to reduce losses due to fraudulent transactions.
Limitations
Anonymized variables in the dataset limit the interpretability of results.
Random undersampling may limit model performance due to reduced training data.
