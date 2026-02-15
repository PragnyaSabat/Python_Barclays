# 📊 Financial Risk Analysis with Python – Barclays Case Study
## 🔎 Project Overview

This project simulates a real-world business scenario where I worked as a Financial Data Analyst for Barclays to analyze customer financial behavior and identify potential financial risk patterns.

With the rapid increase in digital transactions and diversified account usage, the objective was to:

Understand customer interaction across account types (Savings, Current, Credit, etc.)

Analyze debit vs. credit transaction trends

Detect high-risk and irregular financial activity

Identify behavioral indicators linked to low balances or overdrafts

The complete analysis was performed using Python for data cleaning, exploratory data analysis (EDA), segmentation, anomaly detection, and hypothesis testing.

## 🎯 Business Objective

To build a Customer Financial Behavior & Risk Intelligence Report that:

Cleans and consolidates transactional banking data

Extracts actionable behavioral insights

Identifies financial risk patterns

Supports data-driven decision-making for customer engagement and monitoring

## 📁 Dataset Description

The dataset contains transactional-level banking data including:

Column	Description
TransactionID	Unique transaction identifier
CustomerID	Unique customer identifier
AccountID	Unique bank account ID
AccountType	Savings, Loan, Credit, etc.
TransactionType	Deposit, Withdrawal, Transfer, Payment
TransactionDate	Date of transaction
TransactionAmount	Amount transacted
AccountBalance	Post-transaction balance
RiskScore	Customer/transaction risk score
CreditRating	Creditworthiness score
TenureMonths	Relationship duration

(As described in the project brief – Page 2 

C5_Project_Financial Risk Analy…

)

### 🧹 Task 1: Data Cleaning & Preprocessing
✔ Key Actions Performed:

Removed special characters from financial columns

Converted currency values into numerical format

Standardized date formats

Ensured uniform account and transaction categories

Validated missing values and handled inconsistencies

This step ensured analytical integrity and prevented aggregation bias.

### 📈 Task 2: Descriptive Transactional Analysis
✔ Monthly & Yearly Financial Summary

Computed total credits, debits, and net inflow

Created time-based aggregations

✔ Trend Analysis

Visualized debit vs. credit trends over time

Identified seasonality patterns

✔ Account Performance Ranking

Top-performing accounts based on net inflow

Bottom-performing accounts with negative net trends

✔ Dormancy Detection

Accounts were flagged as dormant if:

There was a gap of ≥ 2 months between consecutive transactions

This helped identify potential churn risk.

## 👤 Task 3: Customer Profiling & Segmentation
### 🔹 Activity-Based Segmentation

Accounts classified into:

High Activity – High transaction frequency

Medium Activity

Low Activity

(Rubric clearly defined in analysis notebook)

### 🔹 Balance & Volume Segmentation

Customers segmented using:

Average balance

Total transaction volume

Frequency metrics

### 🔹 Profile Categories Created

High Net Inflow Accounts

High Frequency – Low Balance Accounts

Negative / Near-Zero Balance Accounts

This segmentation helped identify:

Profitable customers

Liquidity-stressed customers

Operational risk exposure

## ⚠️ Task 4: Financial Risk Identification
### ✔ Risk Indicators Tracked:

Frequent large withdrawals

Overdraft behavior

High balance volatility

### ✔ Statistical Risk Measures Used:

Standard Deviation of balance

Coefficient of Variation

IQR method for outlier detection

Z-score anomaly detection

This enabled detection of irregular or suspicious transactional behavior.

## 📊 Task 5: Exploratory Data Analysis (EDA)

Created business-focused visualizations including:

Monthly debit vs. credit trends

Account performance distribution

Balance volatility distribution

Risk score segmentation charts

Transaction frequency histograms

All visualizations were designed for executive-level interpretability.

## 📐 Task 6: Hypothesis Testing
Research Question:

Do high-volume transaction accounts maintain statistically higher average balances than low-volume accounts?

Approach:

Segmented accounts by transaction volume

Performed statistical hypothesis testing

Evaluated significance levels

This validated whether transaction behavior correlates with liquidity strength.

## 🎥 Task 7: Executive Summary Video

A 5-minute video presentation was created summarizing:

Key financial behavior patterns

Risk drivers

Strategic recommendations

Data-backed insights

(Video link included in project documentation as per submission guidelines – Page 4 

C5_Project_Financial Risk Analy…

)

## 🧠 Key Insights Derived

Certain account types showed consistently higher net inflow trends

High-frequency accounts were not always high-balance accounts

Balance volatility strongly correlated with financial risk scores

Dormancy patterns indicated potential churn clusters

Large withdrawal concentration increased short-term liquidity risk

## 💡 Business Recommendations

Monitor high-volatility accounts using automated alerts

Introduce engagement programs for dormant accounts

Implement predictive monitoring for near-zero balance customers

Segment communication strategies based on transaction intensity

Use anomaly detection models for fraud/risk early warning systems

## 🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib / Seaborn

SciPy (Hypothesis Testing)

Jupyter Notebook

📂 Repository Structure
Financial-Risk-Analysis/
│
├── data/
│   └── barclays_transaction_data.csv
│
├── notebooks/
│   └── financial_risk_analysis.ipynb
│
├── visuals/
│   └── charts_and_graphs.png
│
├── summary_report.pdf
├── presentation_video_link.txt
└── README.md

## 📌 Evaluation Criteria Followed

As specified in the project brief 

C5_Project_Financial Risk Analy…

, the project adheres to:

Clear segmentation criteria

Well-documented code

Insight-driven analysis

Statistical validation

High-quality visualizations

Practical, feasible business recommendations

## 🚀 Why This Project Matters

This project demonstrates:

End-to-end financial data analysis

Risk modeling fundamentals

Statistical testing capability

Business problem translation into analytics

Executive-ready reporting

It simulates a real banking analytics use case, aligning strongly with roles in:

Data Analytics

Financial Risk Analytics

Banking Analytics

Business Intelligence

Credit Risk & Fraud Analytics
