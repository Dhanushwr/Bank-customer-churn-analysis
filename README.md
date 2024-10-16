# Bank Customer Churn Data Analysis

---

## Overview
This project focuses on analyzing customer churn for a European bank. By examining various factors such as demographics, tenure, credit score, and product usage, we aim to identify the key drivers of churn and propose recommendations for improving customer retention.

## Dataset
- **Source:** Public dataset from [Kaggle](https://www.kaggle.com/datasets/shubhammeshram579/bank-customer-churn-prediction).
- **Fields:** 
  - `CustomerID`: Unique identifier for customers
  - `CreditScore`: Customer's credit score
  - `Geography`: Country of the customer (France, Germany, Spain)
  - `Gender`: Male or Female
  - `Age`: Age of the customer
  - `Tenure`: Number of years with the bank
  - `Balance`: Customer's account balance
  - `NumOfProducts`: Number of products owned by the customer
  - `HasCrCard`: Whether the customer has a credit card (1 = Yes, 0 = No)
  - `IsActiveMember`: Whether the customer is an active member (1 = Yes, 0 = No)
  - `EstimatedSalary`: Customer's salary estimate
  - `Exited`: Whether the customer churned (1 = Yes, 0 = No)

## Objectives
1. Identify the characteristics of churned customers.
2. Analyze the key factors contributing to churn.
3. Propose strategies to improve customer retention.

## Key SQL Queries
- **Age Group Analysis**
- **Gender Analysis**
- **Geography Analysis**
- **Credit Score Analysis** 
- **Tenure analysis**
- **Credit card analysis**
- **Bank balance analysis**
- **Salary analysis**
- **Activity analysis**
- **Product analysis**

## Findings
1. **Gender Analysis:** **Female customers** have a higher churn rate (25.07%) than male customers (16.46%). 
2.. **Geography Analysis:** Germany exhibits the highest churn rate (32.44%), indicating potential dissatisfaction in that region. 
4. **Tenure Analysis:** The highest number of customers exited after 1 year of tenure, followed by 0 years and 2 years. This suggests that customers are more likely to churn within the first few years of their relationship with the bank.
5. **Number of Products:** Customers with four and only one product have the highest churn rate (100% & 27.7% respectively). 
6. **Active Member Status:** **Inactive members** are more likely to churn, with a churn rate of **26.1%**, compared to only **14.9%** for active members. 
7. **Credit Card Usage:** Customers **without a credit card** show a slightly higher churn rate (**22.0%**) than those with a credit card (**18.6%**).   
8. **Salary Analysis:** Customers earning between **0 - 20k** have a churn rate of **20.12%** (198 exited out of 981 total). Churn increases with salary, peaking at the **150k - 200k** range, with **527 exited** customers.**Higher salary ranges** indicate better retention, with the **50k - 100k** range having the lowest churn rate (**20.0%**). 
9. **Balance Analysis:** Customers with a **balance between 0 - 20k** exhibit the highest churn rate (**13.85%**), with **502 exited** out of **3621 total**. Churn rates decrease with higher balances; those with balances above **200k** show the least churn, although the sample size is small. 
10. **Credit Score Analysis:** Customers with **Mid credit scores** (around 600) are more prone to churn, with rates exceeding **30%**. High credit score and low credit customers are more likely to stay. 
11. **Findings from Age Analysis:** Customers (41-50) exhibit high churn, ratesnindicating a need for targeted retention strategies across different age groups. 


## Visualizations
Dashboard insights are provided in the [`dashboards`](https://github.com/Dhanushwr/Bank-customer-churn-analysis/tree/main/Dashboard) folder.

## License
This project is licensed under Deed - CC0 1.0 Universal License. See [License](https://creativecommons.org/publicdomain/zero/1.0/) for details.
