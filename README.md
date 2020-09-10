# Credit-Card-Fraud-Detection

This dataset contains around 285K credit card transaction records. It has 28 principle components, and 1 'transaction amount' feature. The label, 'class', indicates whether a transaction is a fraud.

Credit card fraud detection is cost sensitive since the cost related to each prediction case is different. In the project, cost of dealing each suspended fraud transaction was assumed to be $5.

Logitstic regression, Random Forest, and a cost classification model based on logit were used to fit the data. Cost classification got the best cost-savings (compared to a pre-determined extreme cost), Random Forest earn the best ROC AUC score.

