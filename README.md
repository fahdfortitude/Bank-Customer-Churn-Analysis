# Bank-Customer-Churn-Analysis for an Anonymous Bank
The Prediction of whether customers will stop carrying out their transactions in a bank
<b>Data source :</b> Analytics Vidhya

### Data Dictionary
There are multiple variables in the dataset which can be cleanly divided in 3 categories:


#### Demographic information about customers

* <b>customer_id</b> - Customer id

* <b>vintage</b> - Vintage of the customer with the bank in number of days

* <b>age</b> - Age of customer

* <b>gender</b> - Gender of customer

* <b>dependents</b> - Number of dependents

* <b>occupation</b> - Occupation of the customer 

* <b>city</b> - City of customer (anonymised)


#### Customer Bank Relationship

* <b>customer_nw_category</b> - Net worth of customer (3:Low 2:Medium 1:High)

* <b>branch_code</b> - Branch Code for customer account

* <b>days_since_last_transaction</b> - No of Days Since Last Credit in Last 1 year


#### Transactional Information

* <b>current_balance</b> - Balance as of today

* <b>previous_month_end_balance</b> - End of Month Balance of previous month


* <b>average_monthly_balance_prevQ</b> - Average monthly balances (AMB) in Previous Quarter

* <b>average_monthly_balance_prevQ2</b> - Average monthly balances (AMB) in previous to previous quarter

* <b>current_month_credit</b> - Total Credit Amount current month

* <b>previous_month_credit</b> - Total Credit Amount previous month

* <b>current_month_debit</b> - Total Debit Amount current month

* <b>previous_month_debit</b> - Total Debit Amount previous month

* <b>current_month_balance</b> - Average Balance of current month

* <b>previous_month_balance</b> - Average Balance of previous month

* <b>churn</b> - Average balance of customer falls below minimum balance in the next quarter (1/0)

## Table of Contents
1. [Exploratory Data Analysis](https://github.com/fahdfortitude/Bank-Customer-Churn-Analysis/blob/main/Churn%20EDA.ipynb) 
2. [Machine Learning](https://github.com/fahdfortitude/Bank-Customer-Churn-Analysis/blob/main/Churn%20machine%20learning.ipynb)
