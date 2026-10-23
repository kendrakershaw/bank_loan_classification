# Universal Bank Personal Loan Classification

## Project Objective
This project analyzes 5,000 customer records to predict personal loan acceptance using logistic regression, decision trees, and neural networks. The decision tree performed the best with 98.5% accuracy, 92.9% precision, and 91% recall. The results will help identify key customer segments to improve marketing efficiency and reduce costs. 

The objective of this project is to develop a binary classification model to predict which Universal Bank customers were most likely to accept a personal loan offer based on important features that were identified through forward stepwise feature selection. By identifying customers more likely to accept a personal loan, the bank could focus its marketing efforts on those customers and avoid unnecessary costs. Since the dataset was imbalanced, we focused on precision, recall, and F1-score to better evaluate how well the models performed.

## Data Set Used
[Universal Bank Customer Data](https://github.com/kendrakershaw/bank_loan_classification/blob/main/UniversalBank.csv)

## Model Performance

### Decision Tree

Each leaf shows the proportion of training customers that landed there and the predicted class. Two leaves account for most of the predicted acceptors: 
- Customers with Income at or above roughly $115K and Education at Graduate or Advanced level: high acceptance probability.
- Customers with Income at or above roughly $115K, an Undergraduate degree, and a Family size of three or more: high acceptance probability.

A smaller third leaf flags mid-income customers (Income roughly $93–107K) with a graduate or advanced degree and elevated monthly credit card spend (CCAvg at or above roughly $3K/month).
![Screenshot(495)](https://github.com/kendrakershaw/bank_loan_classification/blob/main/decision_tree.png)

### Artificial Neural Network



![Screenshot(495)](https://github.com/kendrakershaw/bank_loan_classification/blob/main/ann.png)

![Screenshot(495)](https://github.com/kendrakershaw/bank_loan_classification/blob/main/model_results.png)
