# Fraud Detection
## Introduction
Credit card fraud can be defined as a form of identity theft where someone fraudulently obtains someone else's credit card information to charge purchases or withdraw funds from the account. While cardholders can avoid the financial liability for fraudulent transactions, it can be costly for businesses. Lost of revenue, written-off cost of the product, and chargeback fee can be the outcomes for merchants who lost a dispute or chose not to fight.
## Purpose
The purpose of this project is to compare the performances of three machine learning algorithms for credit card fraud detection.
## Data Understanding
- The dataset is from <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">Kaggle</a>. 
- There are 31 features. 
- A feature called 'Time' contains the number of seconds elapsed between the first transaction and the transaction in the dataset. In this project, feature 'Time' is not used. Features V1, V2, ... V28 are the main components obtained with PCA and the only features that are not transformed with PCA are 'Time' and 'Amount'. The transaction amount is contained in feature 'Amount'. This feature can be used, for example, for cost-aware learning. The feature "Class" is the response variable and takes the value 1 if it is fraud and 0 otherwise.
