# Telco customer churn modelling
Analysis of the factors that could have an impact on customer churn from the telecom operator.
An attempt to predict which customers may opt out of the telecommunications operator's services.

File in the repository:

:point_right: [Telco_Customer_Churn_Modelling.ipynb - Link to Google Colab](https://colab.research.google.com/github/blondeincode/Telco_customer_churn_modelling/blob/main/Telco_Customer_Churn_Modelling.ipynb)

## Project Overview

* generated a basic report on the input data frame using pandas_profiling;
* missing data in the 'TotalCharges' column have been supplemented with the median value in this column;
* data visualizations were created;
* data was divided into training data (70%) and testing data (30%);
* the following machine learning methods were tested: logistic regression, support vector machine, random forest, k-nearest neighbor, decision tree;
* churn probability for each client was calculated.

## Data was downloaded from the website [kaggle.com](https://www.kaggle.com/blastchar/telco-customer-churn)

<details>
  <summary><b>Description of the churn set</b></summary>
  
+ customerID - customer identification number
+ gender - gender
+ SeniorCitizen - is it an elderly person
+ Partner - does he have a partner
+ Dependents - does it have any dependencies
+ tenure - how many months are there already with this operator
+ PhoneService - does it have a telephone?
+ MultipleLines - Whether it has multiple phone numbers
+ InternetService - does it have internet
+ OnlineSecurity - Does it have an online security service
+ OnlineBackup - Does it have an online data backup service
+ DeviceProtection - Whether it has a phone security service
+ TechSupport - does it have a technical support service
+ StreamingTV - does it have a TV streaming option
+ StreamingMovies - Does it have a streaming movie option
+ Contract - whether it has a fixed-term (one or 2-year) or an indefinite (month-to-month) contract
+ PaperlessBilling - e-invoice
+ PaymentMethod - payment method
+ MonthlyCharges - monthly fees
+ TotalCharges - total amount of fees
+ churn - whether the client has left or not
</details>

### Machine learning algorithms used and their prediction accuracy

Model | Score
-------------------- | --------
Logistic Regression  | 80.03
Support Vector       | 79.37
Random Forest        | 78.75
K-Nearest Neighbor   | 76.43
Decision Tree        | 72.36

