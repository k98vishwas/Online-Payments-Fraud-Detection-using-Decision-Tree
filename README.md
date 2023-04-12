# Online-Payments-Fraud-Detection-using-Decision-Tree

## Introduction

### The adoption of digital payment methods has undoubtedly improved the convenience of making payments. However, this has also led to a surge in fraudulent activities related to online payments. Payment fraud can occur with any payment system, particularly when credit cards are used to make payments. Therefore, it is crucial for credit card companies to identify and prevent online payment frauds to safeguard their customers from being billed for goods and services they never authorized. This article aims to provide insights into detecting online payment fraud through the use of machine learning techniques with Python programming.

### OPFD with Machine Learning

### To employ machine learning in the detection of online payment fraud, it is imperative to train a machine learning model to classify payments as fraudulent or non-fraudulent. This necessitates obtaining a dataset that encompasses information on online payment fraud to gain insight into the nature of transactions that are susceptible to fraudulent activities. In this regard, a suitable dataset was collected from Kaggle, which contains comprehensive historical data on fraudulent transactions. This dataset can be leveraged to identify and flag fraudulent online payments. The dataset comprises various columns that contain relevant information on fraudulent transactions.

1️⃣ Step: A unit of time that represents one hour. This refers to the time at which an online transaction occurred.

2️⃣ Type: Refers to the type of online transaction that took place. This could be a purchase, transfer, or any other type of financial activity.

3️⃣ Amount: The amount of money involved in the transaction. This could be any currency, such as USD, EUR, or GBP.

4️⃣ NameOrig: The name of the customer who initiated the transaction. This refers to the person who was sending the money.

5️⃣ OldbalanceOrg: The balance in the customer's account before the transaction took place. This refers to the amount of money that the customer had in their account prior to initiating the transaction.

6️⃣ NewbalanceOrig: The balance in the customer's account after the transaction took place. This refers to the amount of money that the customer had in their account after the transaction was completed.

7️⃣ NameDest: The name of the recipient of the transaction. This refers to the person who received the money.

8️⃣ OldbalanceDest: The balance in the recipient's account before the transaction took place. This refers to the amount of money that the recipient had in their account prior to receiving the money.

9️⃣ NewbalanceDest: The balance in the recipient's account after the transaction took place. This refers to the amount of money that the recipient had in their account after receiving the money.

🔟 IsFraud: Indicates whether the transaction was fraudulent or not. This refers to whether the transaction was a legitimate financial activity or an attempt to deceive or steal money.
