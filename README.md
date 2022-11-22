# Fraud Detection
## Introduction
Credit card fraud can be defined as a form of identity theft where someone fraudulently obtains someone else's credit card information to charge purchases or withdraw funds from the account. While cardholders can avoid the financial liability for fraudulent transactions, it can be costly for businesses. Lost of revenue, written-off cost of the product, and chargeback fee can be the outcomes for merchants who lost a dispute or chose not to fight.
## Purpose
The purpose of this project is to compare the performances of three machine learning algorithms for credit card fraud detection.
## Data Understanding
- The dataset is from <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">Kaggle</a>. 
- There are 31 features. 
- A feature called 'Time' contains the number of seconds elapsed between the first transaction and the transaction in the dataset. In this project, feature 'Time' is not used. Features V1, V2, ... V28 are the main components obtained with PCA and the only features that are not transformed with PCA are 'Time' and 'Amount'. The transaction amount is contained in feature 'Amount'. This feature can be used, for example, for cost-aware learning. The feature "Class" is the response variable and takes the value 1 if it is fraud and 0 otherwise.
## Reference
1. Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi. Calibrating Probability with Undersampling for Unbalanced Classification. In Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015
2. Dal Pozzolo, Andrea; Caelen, Olivier; Le Borgne, Yann-Ael; Waterschoot, Serge; Bontempi, Gianluca. Learned lessons in credit card fraud detection from a practitioner perspective, Expert systems with applications,41,10,4915-4928,2014, Pergamon
3. Dal Pozzolo, Andrea; Boracchi, Giacomo; Caelen, Olivier; Alippi, Cesare; Bontempi, Gianluca. Credit card fraud detection: a realistic modeling and a novel learning strategy, IEEE transactions on neural networks and learning systems,29,8,3784-3797,2018,IEEE
4. Dal Pozzolo, Andrea Adaptive Machine learning for credit card fraud detection ULB MLG PhD thesis (supervised by G. Bontempi)
5. Carcillo, Fabrizio; Dal Pozzolo, Andrea; Le Borgne, Yann-Aël; Caelen, Olivier; Mazzer, Yannis; Bontempi, Gianluca. Scarff: a scalable framework for streaming credit card fraud detection with Spark, Information fusion,41, 182-194,2018,Elsevier
6. Carcillo, Fabrizio; Le Borgne, Yann-Aël; Caelen, Olivier; Bontempi, Gianluca. Streaming active learning strategies for real-life credit card fraud detection: assessment and visualization, International Journal of Data Science and Analytics, 5,4,285-300,2018,Springer International Publishing
7. Bertrand Lebichot, Yann-Aël Le Borgne, Liyun He, Frederic Oblé, Gianluca Bontempi Deep-Learning Domain Adaptation Techniques for Credit Cards Fraud Detection, INNSBDDL 2019: Recent Advances in Big Data and Deep Learning, pp 78-88, 2019
8. Fabrizio Carcillo, Yann-Aël Le Borgne, Olivier Caelen, Frederic Oblé, Gianluca Bontempi Combining Unsupervised and Supervised Learning in Credit Card Fraud Detection Information Sciences, 2019
9. Yann-Aël Le Borgne, Gianluca Bontempi Reproducible machine Learning for Credit Card Fraud Detection - Practical Handbook
10. Bertrand Lebichot, Gianmarco Paldino, Wissam Siblini, Liyun He, Frederic Oblé, Gianluca Bontempi Incremental learning strategies for credit cards fraud detection, IInternational Journal of Data Science and Analytics
11. Credit Card Fraud: What Small Businesses Can Do. https://www.nerdwallet.com/article/small-business/credit-card-fraud#:~:text=Credit%20card%20fraud%20can%20impact,it%20has%20to%20deal%20with
12. Credit Card Fraud. https://www.findlaw.com/criminal/criminal-charges/credit-debit-card-fraud.html
