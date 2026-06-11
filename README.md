🏦 Bank Loan Analysis Dashboard | SQL & Power BI
📌 Project Overview

The Bank Loan Analysis Dashboard is an end-to-end Data Analytics project developed using MS SQL Server and Power BI. The project focuses on analyzing loan applications, funded amounts, repayments, borrower behavior, and loan performance to help financial institutions make data-driven decisions.

This project demonstrates skills in:

Data Extraction
SQL Querying
KPI Development
Data Modeling
Data Visualization
Business Intelligence
Dashboard Design
Financial Data Analysis
🎯 Business Problem

Banks need a comprehensive system to monitor:

Loan Applications
Funded Amounts
Repayment Performance
Good Loans vs Bad Loans
Borrower Risk Profiles
Regional Lending Trends
Loan Portfolio Health

The objective was to transform raw loan data into actionable business insights through interactive dashboards.

🛠️ Tools & Technologies
Tool	Purpose
MS SQL Server	Data Storage & Analysis
SQL Server Management Studio (SSMS)	Query Execution
Power BI	Dashboard Development
Power Query	Data Transformation
DAX	KPI Calculations
Excel	Data Validation
📂 Project Workflow
1️⃣ Data Import & Database Creation
Imported loan dataset into SQL Server.
Created database and tables.
Performed data validation and preparation.
2️⃣ SQL Analysis

Developed SQL queries to calculate:

Total Loan Applications
Funded Amount
Amount Received
Average Interest Rate
Average Debt-to-Income Ratio (DTI)
Good Loan Metrics
Bad Loan Metrics
Monthly Loan Trends
State-wise Analysis
Purpose-wise Analysis
Home Ownership Analysis
3️⃣ Power BI Dashboard Development

Created three interactive dashboards:

Dashboard 1: Summary

KPIs Included:

Total Loan Applications
Month-to-Date (MTD) Loan Applications
Total Funded Amount
Total Amount Received
Average Interest Rate
Average DTI
Good Loan Percentage
Bad Loan Percentage
Loan Status Analysis

Dashboard 2: Overview

Visualizations Included:

📈 Monthly Trends Analysis

🗺️ State-wise Lending Analysis

🍩 Loan Term Distribution

📊 Employment Length Analysis

📉 Loan Purpose Breakdown

🏠 Home Ownership Analysis

These visuals help identify patterns, borrower behavior, and lending opportunities.

Dashboard 3: Details

A detailed reporting dashboard that provides:

Loan Portfolio Overview
Borrower Information
Loan Performance Metrics
Interactive Filtering
Drill-down Analysis

Designed as a one-stop solution for stakeholders requiring detailed loan insights.

📊 Key KPIs Calculated
Loan Metrics
Total Loan Applications
MTD Loan Applications
PMTD Loan Applications
Total Funded Amount
MTD Funded Amount
Total Amount Received
Average Interest Rate
Average DTI
Good Loan Metrics
Good Loan Percentage
Good Loan Applications
Good Loan Funded Amount
Good Loan Amount Received
Bad Loan Metrics
Bad Loan Percentage
Bad Loan Applications
Bad Loan Funded Amount
Bad Loan Amount Received

📈 SQL Concepts Used
SELECT COUNT(id) AS TOTAL_LOAN_APPLICATION
FROM BANK_LOAN_DATA;
SELECT SUM(loan_amount) AS TOTAL_FUNDED_AMOUNT
FROM BANK_LOAN_DATA;
SELECT ROUND(AVG(int_rate),4)*100 AS AVG_INTEREST_RATE
FROM BANK_LOAN_DATA;
SELECT loan_status,
       COUNT(id),
       SUM(loan_amount)
FROM BANK_LOAN_DATA
GROUP BY loan_status;
📋 Business Insights Generated

✔ Loan repayment performance tracking

✔ Good vs Bad loan portfolio assessment

✔ Regional lending analysis

✔ Borrower employment impact analysis

✔ Loan purpose distribution analysis

✔ Home ownership-based lending trends

✔ Interest rate and DTI evaluation

✔ Month-over-Month lending performance analysis

🧠 Skills Demonstrated
SQL
SELECT Statements
Aggregate Functions
GROUP BY
ORDER BY
COUNT
SUM
AVG
CASE Statements
Date Functions
CTEs
Window Functions
Power BI
Data Modeling
Power Query
DAX Measures
Time Intelligence
KPI Cards
Interactive Dashboards
Navigation & Drill-through

📷 Dashboard Preview

Add screenshots here:

Bank Loan Dashboard Screenshots
│
├── Dashboard 1 - Summary.png
├── Dashboard 2 - Overview.png
└── Dashboard 3 - Details.png
🚀 Project Outcomes

This project helped me gain practical experience in:

Financial Data Analytics
SQL Query Optimization
Business Intelligence Reporting
KPI Development
Interactive Dashboard Design
End-to-End Data Analysis Workflow
👨‍💻 Author
Pranav Saratkar

🎓 BCA Student | Aspiring Data Analyst

📧 Email: pranav.saratkar.work@gmail.com
🔗 LinkedIn: 

💼 Skills: SQL • Power BI • Python • Excel • Data Analytics
