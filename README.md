# Churn-Prediction-ML
Machine Learning Project: Customer Churn Prediction

In this project, we will analyze a bank's customer churn using logistic regression. We can classify customer information in 3 different categories.

## Demographic information about customers

- **customer_id** - Uniquely identifies customer
- **vintage** - Since when is the customer of the bank as a day
- **age** - Customer's age
- **gender** - Customer's gender
- **dependents** - Number of dependents
- **occupation** - Customer's job
- **city** - Where the customer lives

## Customer Bank Relationship

- **customer_nw_categor** - Customer's wealth(Net Worth) (3:Low 2:Medium 1:High)
- **branch_code** - Branch Code for account
- **days_since_last_transaction** - Number of days since last credit in last one year

## Transactional Information

- **current_balance** - Balance as of today
- **previous_month_end_balance** - End of Month Balance of previous month
- **average_monthly_balance_prevQ** - Average monthly balances (AMB) in Previous Quarter
- **average_monthly_balance_prevQ2** - Average monthly balances (AMB) in previous to previous quarter
- **current_month_credit** - Total Credit Amount current month
- **previous_month_credit** - Total Credit Amount previous month
- **current_month_debi** - Total Debit Amount current month
- **previous_month_debit** - Total Debit Amount previous month
- **current_month_balance** - Average Balance of current month
- **previous_month_balance** - Average Balance of previous month
- **churn** - Average balance of customer falls below minimum balance in the next quarter (1/0)