# Churn Prediction using Machine Learning

![Issues](https://img.shields.io/github/issues/shlok-sethia/Churn-Prophecy)
[![License](https://img.shields.io/github/license/shlok-sethia/Churn-Prophecy)](https://github.com/shlok-sethia/Churn-Prophecy/blob/master/LICENSE)
![](https://img.shields.io/github/repo-size/shlok-sethia/Churn-Prophecy.svg?label=Repo%20size&style=flat-square)&nbsp;


![Test Image 1](assets/Churn.png)

Problem Statement
----------------------------

### Business Problem Overview
In the banking industry, customers are able to choose from multiple service providers and actively switch from one bank to another. In this highly competitive market, the banking industry experiences an average of 20-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, **customer retention** has now become even more important than customer acquisition.
 
For many incumbent banks, *retaining high profitable customers is the number one business goal*.
 
To reduce customer churn, banks **need to predict which customers are at high risk of churn**.
 
In this project, you will analyse customer-level data of a leading banking firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

The **business objective** is to predict a set of customers who might churn in the coming months, so that appropriate actions can be taken to retain them. To do this task well, understanding the typical customer behaviour during churn will be helpful.
 
### Definitions of Churn

There are various ways to define churn, such as:
**Usage-based churn:** Customers who have not done any usage over a period of time or have a zero-balance account.
 
A potential shortcoming of this definition is that when the customer has stopped using the services for a while. For e.g., if you define churn based on a ‘six-months zero usage’ period, predicting churn could be useless since not most customers transact that frequently.

**Service-provider based churn:** Customers who have changed their service provider by permanently closing their account, it may be too late to take any corrective actions to retain them. So if we can predict such customers we can take some action before its too late
 
In this project, you will use the **Service-provider based definition** to define churn.
