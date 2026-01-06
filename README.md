# Banking Analytics- FinInsight Group (Power BI Dashboard)
Dashboard Overview:

An end-to-end banking data analysis project built using Power BI to analyze transactions, customer accounts, credit scores, loans, and branch performance. The project focuses on uncovering patterns in customer behavior, financial health, risk distribution, and operational performance to support data-driven decision making.

## Problem Statement

Banks generate large volumes of transactional and customer data every day.
However, without proper analysis, it is difficult to:

Understand customer transaction behavior

Identify high-risk accounts and unusual transactions

Analyze branch performance

Study the relationship between credit score, loan amount, and balances

Track trends over time

The objective of this project was to analyze banking transactions and customer account data and build an interactive Power BI dashboard to extract meaningful insights for business and operational decisions.

## Datasets Used

Two datasets were used:

1. Banking Transactions Dataset

Contains:

- Transaction ID

- Account Number

- Transaction Type (Deposit, Withdrawal, Payment, Transfer)

- Amount & Currency

- Transaction Date & Time

- Branch Code

2. Customer Account Details Dataset

Contains:

- Account Number (Primary Key)

- Account Holder

- Account Type (Savings, Credit, Loan, Checking)

- Balance

- Interest Rate

- Credit Score

- Loan Amount

- Opening Date

- Account Holder Details (Demographics)

These datasets were connected using AccountNumber as the key.

## Approach
1. Data Cleaning & Preparation

Removed duplicates and handled missing values

Converted data types for consistency

Extracted demographic details from text columns

Standardized currency values

2. Data Modeling

Built relationships between transactions and account tables

Created calculated columns and measures using DAX

Structured the model for efficient filtering and slicing

3. DAX & Analysis

Used DAX to:

Calculate average balance by account type

Create branch performance rating

Identify high-value transactions

Analyze net flow (inflow – outflow)

Categorize credit scores and risk levels

Perform time-based trend analysis

Build basic predictive and risk assessment measures

4. Dashboard Design

Created 3 main dashboards:

Bank Overview & Transactions

Customer, Account & Loan Insights

Customer Trends & Correlation

Added slicers for account type, transaction type, branch, year, and credit score

Focused on clean layout and readability

## Key Analysis Areas
Transaction Analysis

Transaction volume by type (Deposit, Withdrawal, Payment, Transfer)

Transaction trends over time (Year, Quarter, Month)

Transaction time patterns (Morning, Afternoon, Evening, Night)

Currency distribution

Branch Performance

Top branches by transaction value

Branch rating based on volume and value

Branch-wise transaction distribution

Customer & Account Analysis

Average balance by account type

Credit score distribution (Good, Poor, Excellent)

Account opening trends

Customer tenure analysis

Loan & Credit Analysis

Loan amount by account type

Loan amount vs credit score

Risk category distribution

Relationship between account age and balance

Risk & Unusual Transaction Detection

Identification of high-value transactions

Detection of unusual transactions

Risk assessment categorization using DAX

## Dashboards Overview
**1. Bank Overview & Transactions Dashboard**

Total transactions, transaction value, total accounts, total loan amount

Transaction volume by type

Top 5 branches by transaction value

Transaction time patterns

Currency breakdown

Transaction trend over time
<img width="1340" height="771" alt="image" src="https://github.com/user-attachments/assets/18b805c7-d889-4348-aef2-674209f849c7" />

**2. Customer, Account & Loan Insights Dashboard**

Credit score distribution

Loan amount distribution

Loan amount by account type

Customer loan by credit score

Risk category distribution

<img width="1344" height="769" alt="image" src="https://github.com/user-attachments/assets/47f5ac7e-9921-437b-b3fb-3306a59a7b32" />


**3. Customer Trends & Correlation Dashboard**

Account opening trend by month

Correlation between account age and balance

Customer demographics vs transaction behavior

City-wise transaction comparison

<img width="1348" height="760" alt="image" src="https://github.com/user-attachments/assets/0a4abfd9-d30f-41ad-9b21-e1546304181c" />

## Tools & Technologies

Power BI – Dashboarding & Visualization

DAX – Calculated measures and columns

Power Query – Data cleaning & transformation

Excel – Source data format

## Key Insights

Savings and Credit accounts showed higher average balances compared to others

Good and Poor credit score categories had higher loan exposure than Excellent

Certain branches consistently handled higher transaction volumes and values

Most transactions occurred during Morning and Afternoon time slots

Account age showed a mild relationship with balance, but not a strong correlation

High-value and unusual transactions were concentrated in specific accounts and branches

## Conclusion

This project demonstrates how banking data can be transformed into actionable insights using Power BI.
By combining transaction data with customer account details, it becomes easier to:

Understand customer behavior

Monitor branch performance

Identify risk-prone accounts

Track loan exposure

Detect unusual or high-value transactions

The dashboards provide a clear, interactive, and structured view of the banking ecosystem, helping stakeholders make informed decisions related to operations, risk management, and customer strategy.




