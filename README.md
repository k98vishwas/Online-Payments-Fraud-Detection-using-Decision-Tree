# Online-Payments-Fraud-Detection-using-Decision-Tree

## Introduction

### The adoption of digital payment methods has undoubtedly improved the convenience of making payments. However, this has also led to a surge in fraudulent activities related to online payments. Payment fraud can occur with any payment system, particularly when credit cards are used to make payments. Therefore, it is crucial for credit card companies to identify and prevent online payment frauds to safeguard their customers from being billed for goods and services they never authorized. This article aims to provide insights into detecting online payment fraud through the use of machine learning techniques with Python programming.

### OPFD with Machine Learning

### To employ machine learning in the detection of online payment fraud, it is imperative to train a machine learning model to classify payments as fraudulent or non-fraudulent. This necessitates obtaining a dataset that encompasses information on online payment fraud to gain insight into the nature of transactions that are susceptible to fraudulent activities. In this regard, a suitable dataset was collected from Kaggle, which contains comprehensive historical data on fraudulent transactions. This dataset can be leveraged to identify and flag fraudulent online payments. The dataset comprises various columns that contain relevant information on fraudulent transactions.

### Type: This refers to the type of online transaction being conducted. It could be a purchase, a transfer, or any other type of transaction that can be done online.
### Amount: This is the monetary value of the transaction, measured in the currency of the transaction.
### NameOrig: This is the name of the customer who is initiating the transaction.
### NameDest: This is the name of the recipient who will be receiving the funds from the transaction.
### OldbalanceOrg: This is the balance of the customer's account before the transaction is initiated.
### NewbalanceOrig: This is the balance of the customer's account after the transaction is completed.
### OldbalanceDest: This is the initial balance of the recipient's account before the transaction is completed.
### NewbalanceDest: This is the balance of the recipient's account after the transaction is completed.
### IsFraud: This indicates whether the transaction is a fraudulent transaction or not.
### Step: This represents a unit of time where one step equals one hour. This information is less important compared to the other information listed above, but it may still be relevant in some contexts, such as when analyzing transaction patterns over time.

