# Fraudulent-Transaction-Activity-Detection-
DataSet source: Kaggle
The aim of the report is to compare properties of machine
learning algorithms to learn and apply learned knowledge in
the task of prediction. The type of learning is limited to
Supervised learning. The algorithms which will be applied are
Logistic Regression, K - nearest neighbors, Naïve-Bayes and
Decision tree.
This project aims to predict the fraud transactions in a manner
suited for real world applications.

The broad scope of the Detection of Fraud in Financial
Transactions project includes:
• The system will be available on an online banking system
for 24x365 access to the Cyber Security Personnel of the
bank.
• The system will support Machine Learning based
detection of Fraud Transactions.
• We can predict fraud in a large volume of transactions
by applying cognitive computing technologies to the
raw data.
• This is the reason why machine learning algorithms will
be used by banks for preventing fraud for their clients.

DATA DESCRIPTION
SOURCE OF DATA: https://www.kaggle.com/ntnu-testimon/paysim1
There is a lack of public available datasets on financial services and specially in
the emerging mobile money transactions domain. Financial datasets are
important to many researchers and in particular to us performing research in the
domain of fraud detection. Part of the problem is the intrinsically private nature
of financial transactions, that leads to no publicly available datasets.
We present a synthetic dataset generated using the simulator called PaySim as
an approach to such a problem. PaySim uses aggregated data from the private
dataset to generate a synthetic dataset that resembles the normal operation of
transactions and injects malicious behaviour to later evaluate the performance
of fraud detection methods.
• step (int64) - maps a unit of time in the real world. In this case 1 step is 1 hour
of time. Total steps 744 (30 days simulation).
• type (object) - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.
• Amount (float64) - amount of the transaction in local currency.
• nameOrig(object) - customer who started the transaction.
• oldbalanceOrg (float64) - initial balance before the transaction.
• newbalanceOrig (float64) - new balance after the transaction.
• nameDest (obj)- customer who is the recipient of the transaction.
• oldbalanceDest (float64) - initial balance recipient before the transaction.
• newbalanceDest (float64) - new balance recipient after the transaction.
• isFraud (int64) - This is the transactions made by the fraudulent agents inside
the simulation. In this specific dataset the fraudulent behavior of the agents
aims to profit by taking control or customers accounts and try to empty the
funds by transferring to another account and then cashing out of the system.
• isFlaggedFraud (int64) - The business model aims to control massive transfers
from one account to another and flags illegal attempts. An illegal attempt in
this dataset is an attempt to transfer more than 200.000 in a single transaction.

 
