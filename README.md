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

Cost of Sales increased by 61.92%, while operating expenses rose by 78.01%. Both grew faster than revenue, putting further pressure on profit margins.

Gross profit fell from 16.73% to 11.67% while the loss before tax almost doubled, increasing by ₦684.28m.

The figure shows that although the business generated more sales in 2025, it struggled to control costs associated with those sales.

### 2. Operating Expenses

Operating expenses increased  by ₦693.24m in 2025.
The largest increases came from four departments;

|Department|Increased from 2024
|--------|-----------------|
|Facilities and Administration|₦370.97m
|Logistics and Fleet|₦148.49m
|Finance and Accounting|₦63.87m
|Supply Chain and Operations|₦52.28m

Facilities and administration accounted for more than half of the overall increase in operating expenses. Generator and diesel and fuel costs were the main contributor, rising by ₦320.44m within the department.

Logistics and fleet recorded the second largest increase, mainly due to an additional spent on outbound freight and delivery.

Facilities and administration and logistics accounted for approximately 75% of increase in operating expenses.

### 3. Cost of Sales

Cost of sales rose increased from ₦1.17billion in 2024 to ₦1.90billion in 2025, an increase in ₦726.97million.

This increase came from three accounts;

|Category|Increased from 2024
|--------|-----------------|
|Finished goods purchase|₦345.69m
|Importation and custom clearance|₦227.96m
|Inbound freight and primary transportation|₦144.89m

These three accounts represented approximately 98.8% of the total increase in cost of sales. With direct cost growing faster than revenue, the business retained less gross profit from each sales.

A closer review of purchasing costs, importation expenses and inbound transportation would help management underatand where cost could be reduced withouth affecting operations.

### 4. Branch Profitability

All eight branches recorded negative profit margins in 2025.

Abuja Central performed relatively better than the other branches, with an operating profit of -18.65%. Benin recorded the weakest margin at -97.49%.

Lagos Mainland recorded the largest operating loss in absolute terms, at approximately ₦370.12million.

These results suggest that management should apply the same approach to every brnach. Branches with negative gross profit need particular attention, while Lagos Mainland warrants a closer review because of the size of its operating loss.

### 5. Overall Assessment
The main issue in 2025 was not lack of revenue growth. Sales increased considearbly, but the business spent more to generate and support the revenue.

Rising direct cost reduced profit margin, while hihger operating expenditure added firther pressure on profitabilty.

The analysis highlights three areas worth prioritising; energy costs, logistics expenditure and gross margin improvement.

It is therefore advised to investigate the reasons behind these costs increase and identify practical changes that could improve financial performannce.





