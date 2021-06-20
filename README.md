# Churn Prediction using Machine Learning

![Issues](https://img.shields.io/github/issues/shlok-sethia/Churn-Prophecy)
[![License](https://img.shields.io/github/license/shlok-sethia/Churn-Prophecy)](https://github.com/shlok-sethia/Churn-Prophecy/blob/master/LICENSE)
![](https://img.shields.io/github/repo-size/shlok-sethia/Churn-Prophecy.svg?label=Repo%20size&style=flat-square)&nbsp;


![Test Image 1](assets/Churn.png)

Problem Statement - Business Problem Overview
----------------------------
In the banking industry, customers are able to choose from multiple service providers and actively switch from one bank to another. In this highly competitive market, the banking industry experiences an average of 20-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, **customer retention** has now become even more important than customer acquisition.
 
For many incumbent banks, *retaining high profitable customers is the number one business goal*.
 
To reduce customer churn, banks **need to predict which customers are at high risk of churn**.
 
In this project, you will analyse customer-level data of a leading banking firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

The **business objective** is to predict a set of customers who might churn in the coming months, so that appropriate actions can be taken to retain them. To do this task well, understanding the typical customer behaviour during churn will be helpful.
 
Definitions of Churn
----------------------------
There are various ways to define churn, such as:
**Usage-based churn:** Customers who have not done any usage over a period of time or have a zero-balance account.
 
A potential shortcoming of this definition is that when the customer has stopped using the services for a while. For e.g., if you define churn based on a ‘six-months zero usage’ period, predicting churn could be useless since not most customers transact that frequently.

**Service-provider based churn:** Customers who have changed their service provider by permanently closing their account, it may be too late to take any corrective actions to retain them. So if we can predict such customers we can take some action before its too late
 
In this project, you will use the **Service-provider based definition** to define churn.

Dataset
----------------------------
It consists of 10000 observations and 12 variables. Independent variables contain information about customers. Dependent variable refers to customer abandonment status.
### Variables:
**RowNumber** — corresponds to the record (row) number and has no effect on the output.
**CustomerId** — contains random values and acts as a primary key which is unique for each customer. 
**Surname** — the surname of a customer.
**CreditScore** — customers credit score, can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
**Geography** — a customer’s location.
**Gender** — customers gender.
**Age** — this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
**Tenure** — refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
**Balance** — gives the balance in the account. A very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
**NumOfProducts** — refers to the number of products that a customer has purchased through the bank.
**HasCrCard** — denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank. (0=No,1=Yes)
**IsActiveMember** — categorical column suggesting ifa customer is an active user or not. Active customers are less likely to leave the bank. (0=No,1=Yes)
**EstimatedSalary** — estimated salary of an individual, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
**Exited** — whether or not the customer has left the bank. This is what we have to predict. (0=No,1=Yes)
