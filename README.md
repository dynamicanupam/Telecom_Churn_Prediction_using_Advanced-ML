# Telecom Churn Prediction

## Business Problem Overview

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal.

To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

In this case study, we will analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

### Definitions of churn
 There are various ways to define churn, such as:

* *Revenue-based churn:* Customers who have not utilised any revenue-generating facilities such as mobile internet, outgoing calls, SMS etc. over a given period of time. One could also use aggregate metrics such as ‘customers who have generated less than INR 4 per month in total/average/median revenue’.
The main shortcoming of this definition is that there are customers who only receive calls/SMSes from their wage-earning counterparts, i.e. they don’t generate revenue but use the services. For example, many users in rural areas only receive calls from their wage-earning siblings in urban areas.

* *Usage-based churn:* Customers who have not done any usage, either incoming or outgoing - in terms of calls, internet etc. over a period of time.
A potential shortcoming of this definition is that when the customer has stopped using the services for a while, it may be too late to take any corrective actions to retain them. For e.g., if you define churn based on a ‘two-months zero usage’ period, predicting churn could be useless since by that time the customer would have already switched to another operator.

In this project, we will use the usage-based definition to define churn.

## The Approach

We used the CRISP framework for building the model. We did following steps

![image](https://github.com/dynamicanupam/Telecom-Churn-Prediction/assets/61014822/23dfd1c4-2863-4be7-8932-d384da38b40c)

1. Importing the required libraries and reading the dataset.
2. Inspecting and cleaning up the data
3. Perform data encoding on categorical variables
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Feature Scaling
7. Dimensionality Reduction using PCA
8. Model Building
    - Logistic Regression
    - Random Forest
    - Gradient Boosting
    - XGBoost Classifier
    - LGBMClassifier
9. Model Validation (predictions)
    - Accuracy score
    - Confusion matrix
    - ROC and AUC
    - Recall score
    - Precision score
    - F1-score
10. Handling the unbalanced data
    - Class weights
    - Using SMOTE
11. Feature Selection
12. Final Prediction on Unseen data

## Model Evaluation Summary
![image](https://github.com/user-attachments/assets/05674fbe-2434-4f78-b710-8e0ad30d5147)
