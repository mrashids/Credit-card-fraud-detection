# Credit-card-fraud-detection
Predicting potential credit card fraud using decision tree classifier.

FRAUD DETECTOR

E-commerce and many other online sites have increased the online payment modes, increasing the risk for online frauds. Credit card fraud is increasing considerably with the development of modern technology and the global superhighways of communication. Credit card fraud costs consumers and the financial company billions of dollars annually, and fraudsters continuously try to find new rules and tactics to commit illegal actions. It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
Fraud Detector is a service that makes it easy to identify potentially fraudulent online activities such as online Credit card fraud.
Different Supervised machine learning algorithms like Decision Trees and Naive Bayes Classification are used to detect fraudulent transactions.

We analyze the past transaction details of the customers and extract the behavioral patterns. Later classifiers are trained over the groups separately. And then the classifier with better rating score can be chosen to be one of the best methods to predict frauds.

DATASET:
The datasets contain transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation.
Since providing transaction details of a customer is considered to issue related to confidentiality, therefore most of the features in the dataset are transformed using principal component analysis (PCA). V1, V2, V3..., V28 are PCA applied features and rest i.e., ‘time’, ‘amount’ and ‘class’ are non-PCA applied features, as shown in table:

Feature Description: 

Time
Time in seconds to specify the elapses between the current transaction and first transaction.

Amount
Transaction amount

Class
0 - not fraud 

1 – fraud

The size of the file is 144 MBs. It contains 31 columns including the class column and 284,807 records in total.
