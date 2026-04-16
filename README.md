# bank_transaction_system
project 1 of BFSI Technical

# Bank System Database Project

# Overview
This project is a simple bank management system implemented using SQL. It manages customer details and their transactions. The database allows storing, retrieving, and analyzing banking data efficiently.

# Database Name
bank_system

# Tables Used

Customers Table
Stores customer details
Columns
customer_id unique identifier for each customer
name customer name
email customer email address
city customer city
account_type type of account such as savings or current
account_balance current balance in the account

# Transactions Table

Stores transaction details
Columns
transaction_id unique identifier for each transaction
customer_id links to customers table
amount transaction amount positive for credit and negative for debit
transaction_type type of transaction credit or debit
transaction_mode mode of transaction such as UPI ATM NEFT IMPS
transaction_date date and time of transaction

# Key Features

Database creation and table setup
Insertion of sample customer and transaction data
Filtering customers based on balance
Sorting transactions by date
Finding unique transaction modes
Retrieving top transactions
Pattern search on customer names
Aggregation functions like sum and average
Join operations between customers and transactions
Window functions for running totals and ranking

# Queries Implemented

Display all customers and transactions
Find customers with account balance greater than 10000
Sort transactions in descending order of date
Get distinct transaction modes
Find top 5 highest transactions
Search customers whose names start with letter A
Calculate total transaction amount per customer
Find customers with total transactions greater than a specific value
Join customers and transactions to display combined data
Calculate running total of transactions using window function
Rank customers based on account balance
Find customers with above average transaction amounts

# Purpose

This project helps in understanding SQL concepts such as database creation joins aggregation grouping filtering and window functions. It is useful for beginners learning database management and for academic practice.

# Conclusion

The bank system database demonstrates how real world banking data can be managed using SQL. It provides a strong foundation for building more advanced database driven applications.
