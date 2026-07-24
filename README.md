# Fraudulent Credit Card Transactions Detection Using Naive Bayes Classifier

## Project Overview
This project focuses on the detection of fraudulent credit card transactions using a Naive Bayes Classifier. The model leverages machine learning techniques to categorize transactions as either fraudulent or legitimate. It also compares the performance of Naive Bayes with other classifiers like Decision Tree and Logistic Regression.

## Features
- **Dataset**: The dataset consists of credit card transactions made by European cardholders in September 2013. It includes 284,807 transactions, of which 492 are fraudulent.
- **PCA Features**: The public dataset provides anonymized features `V1` through `V28` that were already transformed with PCA by its publisher.
- **Naive Bayes Classifier**: The project builds a Naive Bayes classifier to predict fraudulent transactions based on input features.
- **Data Balancing**: Due to the class imbalance (fraudulent transactions are only 0.17% of the data), undersampling techniques are used.
- **Performance Metrics**: The model evaluates accuracy, recall, precision, and F1-score, comparing Naive Bayes to Scikit-Learn classifiers like Decision Tree and Logistic Regression.


## Results
The project compares multiple machine learning classifiers, with Naive Bayes achieving the following results:
- **Accuracy**: 91%
- **Recall**: 86%
- **Precision**: 93%
- **F1 Score**: 89%

The recorded comparison runs reached approximately 89% accuracy for the Decision Tree and 91% for Logistic Regression on the same undersampled split.

## Future Work
- Implementing genetic algorithms and stacked classifiers for improved fraud detection.
- Exploring more advanced machine learning techniques for feature selection and class imbalance handling.

## Contributors
- Abdulrahman Emad
- Amir Hesham
- Habiba Salama
- Mariam Ahmed
- Muhammad Mosilhy

## References
- Sharma, N.D.K., Chalapathi, N.M.M.V. (2022). "A Novel Machine Learning Technique for Fraud Detection on Credit Card Financial Data".
- Randhawa, K., Loo, C.K., Seera, M., Lim, C.P., Nandi, A.K. (2018). "Credit Card Fraud Detection using AdaBoost and Majority Voting".
---
