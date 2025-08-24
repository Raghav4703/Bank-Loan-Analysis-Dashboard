This project is an end-to-end Data Analytics case study where raw loan data is transformed into actionable insights using MS SQL Server for data processing and Power BI for visualization. The goal is to analyze loan applications, disbursements, repayments, and borrower profiles in order to monitor portfolio performance, identify risks, and assist financial institutions in making data-driven decisions.

🔹** Project Objective**

Banks and financial institutions handle thousands of loan applications every month. To ensure sustainable growth, they need to track how many applications are approved or rejected, how much money is disbursed, how much is repaid, and which borrowers or loan types carry the most risk.

This project aims to:

Build interactive dashboards that summarize key metrics.

Perform Good Loan vs Bad Loan analysis for portfolio health.

Provide borrower-level details for deeper insights.

Enable regional, demographic, and purpose-based breakdowns of loans.

Use SQL queries + Power BI DAX functions to automate insights such as Month-to-Date (MTD) and Month-over-Month (MoM) trends.


🔹** Workflow & Methodology**
1. Data Preparation (MS SQL Server)
Imported raw bank loan data into SQL Server database.
Created tables and schema to manage loan data efficiently.
Performed data cleaning and transformation using SQL:
Handling missing values.
Standardizing date formats with DATENAME, DATEPART, etc.
Type conversions with CAST and DECIMAL.
Aggregating metrics with COUNT, SUM, and AVG.
Using CTEs and partitions for advanced analysis.


2.** Data Analysis (SQL Queries)**
Queries were designed to solve real-world business questions such as:
How many loan applications were received in a given period?
What is the total funded amount vs total received amount?
What is the average interest rate and average DTI (Debt-to-Income ratio)?
How many loans are classified as Good Loans vs Bad Loans?
What are the repayment patterns based on borrower employment length, purpose, or home ownership?
These queries laid the foundation for dashboards in Power BI.


3. **Data Visualization (Power BI)**
The processed data was connected from SQL Server to Power BI, and visual reports were created with DAX measures, calculated columns, and KPIs.
Three key dashboards were designed:


📌 Dashboard 1: Summary

Key KPIs:
Total Loan Applications (with MTD and MoM comparison)
Total Funded Amount (MTD, MoM)
Total Amount Received (MTD, MoM)
Average Interest Rate (MTD, MoM)
Average Debt-to-Income Ratio (MTD, MoM)
Good Loan vs Bad Loan Analysis:
% of Good Loan Applications
Good Loan Funded vs Received Amounts
% of Bad Loan Applications
Bad Loan Funded vs Received Amounts

Loan Status Grid View:
A matrix view to break down loans by status (e.g., Approved, Funded, Paid, Defaulted).


📌 Dashboard 2: Overview
Monthly Trends (Line Chart): Identify seasonality and loan growth patterns.
Regional Analysis (Map): Geographic distribution of lending and repayments across states.
Loan Term Distribution (Donut Chart): Insights into short-term vs long-term borrowing.
Employment Length Analysis (Bar Chart): Loans by borrowers’ years of employment.
Loan Purpose Breakdown (Bar Chart): Business, education, personal, car, home improvement, etc.
Home Ownership Analysis (Tree Map): Relation between ownership type (Own, Rent, Mortgage) and loan performance.


📌 Dashboard 3: Details
A comprehensive data grid consolidating borrower and loan-level details.
Contains metrics like application ID, funded amount, received amount, interest rate, term, employment length, purpose, and repayment status.
Acts as a one-stop solution for loan officers or analysts who need borrower-level insights.


🔹** Key Learnings & Skills Gained**
Writing complex SQL queries using Joins, CTEs, Aggregations, Window Functions.
Building Time Intelligence measures in Power BI (MTD, MoM, YTD).
Creating interactive dashboards with slicers, drill-throughs, and filters.
Performing Good Loan vs Bad Loan KPI analysis.
Delivering a complete data pipeline: Import → Cleaning → SQL Analysis → Visualization.


📌 **Conclusion**
The Bank Loan Analysis Dashboard demonstrates how raw data can be transformed into meaningful business insights through structured data processing and powerful visualizations.
By combining SQL for backend analysis with Power BI for visualization, this project provides a 360° view of loan performance, helping stakeholders:
Monitor loan approvals, disbursements, and repayments.
Identify risky loans early.

Understand borrower behavior and demographics.

Make data-driven financial decisions.
