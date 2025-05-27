# Fraud Detection project
Detecting Recursive Fraudulent Transactions

Question:
  Use a recursive CTE to identify potential money laundering chains where money is transferred from one account to another across multiple steps, with all transactions flagged as fraudulent.

Solution:
  This query uses a recursive CTE to track the flow of money through multiple accounts over successive steps. The recursive part of the CTE allows us to follow the chain of transactions and   identify patterns that could indicate money laundering activities. It filters out chains where all transactions are marked as fraudulent.
