# Financial-Performance-Analysis-2024_2025
## A Comprehensive Financial Performance Review (2024-2025)
### Tools: Microsoft Power BI | Power Query | DAX | Data Modelling | Fianancial Analysis

## Project Overview
This project uses Power BI to analyse the financial performance of a Nigerian business, based on 4,500 transactions recorded between 2024 and 2025.

The analysis examines revenue growth, cost of sales, operating expenses, profitability, departmental spending and branch perfomance.

The key focus is understanding why revenue growth did not result in a correcponding improvement in profitability. This project also identifies areas where costs could be better managed and financial performance improved.

Using financial reporting, data modelling, DAX measures and interactive dashboards, the project provides a clearer picture of business performance and supports informed management decisions.

## Business Objectives

The project focus on five objectives:
  1. Produce a monthly interactive Profit & Loss (Income) Statement.
  2. Compare period-over-period financial performance (2024 vs 2025).
  3. Pinpoint the major operational and macroeconomic expense drivers behind profit margin compression.
  4. Evaluate branch-level and department-level cost efficiencies.
  5. Provide data-backed actionable strategic recommendations for executive leadership.

## Dataset Overview

The dataset contains 4,500 financial transactions recorded between 2024-2025 reporting period, covering eight branches and ten departments.

The financial entries include:
- Transation dates and reference numbers
- Account categories and transaction types
- Revenue and cost amounts in Nigeria (NGN)
- Branch and departmental allocations
- Cost centre classifications
- Payment methods and transactions status

The dataset forms the basis for analysing financial performance, tracking expenses, comparing annual results and identifying trends across the business.

## Data Preparation
I used Power Query to clean and organise the financial data before building the report. This involved checking the data types, reviewing data quality and making sure account, department, branch information was consistent.

Some transactions had missing department or cost centre allocations. Rather than assigning them to categories without support information, I flagged these records separetely to avoid misleading results.

## Data Model
The Power BI reports follows a star schema style structure with FinancialTransaction as the main fact table.

The model included the following tables.
|Table|Description
|--------|-----------------|
|Financial Transactions|Contains the 4,500 financial transactions used in the analysis
|Chart of Accounts|Groups accounts into the categories needed for financial reporting
|Departments|Support departmental expenditure analysis
|Branches|Used to compare financial performance across branches
|Cost Centres|Supply analysis of expenditure by cost centre
|Date Table|Provides the calendar structure for monthly, yearly and time based calculations
PLLayout|A disconnected table used to arrange the Profit and Loss statement

## Power BI Dashboard Overview
This Power BI report includes six interactive pages covering financial performance for 2024 and 2025. Each page focuses on a different area of the business, from overall profitability to branch performance and cost analysis.
1. Financial Dashboard
2. Profit & Loss
3. Branch Profitability
4. Departmental Cost Analysis
5. Cost of Sales Analysis
6. Data Quality Review

## Dashboard Screenshots
Screenshots of all six dashboard pages can be found in the Screenshots folder.

The interactive Power BI file is available in the Power BI folder.

## Key Financial Findings 2024-2025
### 1. Revenue and Profitability

Revenue grew by 52.3% in 2025, rising from ₦1.41billion to ₦2.15billion. Despite this growth, the business recorded a larger loss in the previous year.
|Financial Indicator|2024|2025
|--------|-----------------|--------------|
|Revenue|₦1,410.10b|₦2,152.18b
|Cost of Sales|₦1,174.12b|₦1,901.09b
|Operating Expenses|₦888.65m|₦1,581.89b
|Gross Profit|₦235.97m|₦251.09m
|Gross Profit Margin|16.73%|11.67%
|Operating Profit|-₦652.68m|-₦1,330.8b
|Operating Profit Margin|-46.29%|-61.83%
|Profit Before Tax|-₦691.10m|-₦1,375.38b




