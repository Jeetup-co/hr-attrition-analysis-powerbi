# HR Attrition Analysis Dashboard

![Dashboard Preview](Dashboard%20HR%20Attrition.png)

## Overview
Interactive Power BI dashboard analysing employee attrition
across 1,470 records from the IBM HR Analytics dataset.

## Key Findings
- Overall attrition rate: **16.12%**
- Overtime workers leave at **30.53%** vs 10.44% without overtime
- Sales Representatives highest role attrition at **39.76%**
- Employees below $3k/month have **28.61%** attrition rate

## Tools Used
- Microsoft Power BI Desktop
- DAX (CALCULATE, DIVIDE, COUNTROWS, SELECTEDVALUE)
- Power Query for data transformation
- Python (pandas, SQLite3, matplotlib, seaborn)

## Files
- `HR Attrition Analysis.pbix` — Power BI dashboard file
- `HR_Attrition_Analysis_with_markdown.ipynb` — Python + SQL analysis
- `/data` — Source CSV files (5 tables)

## DAX Measures Written
- Total Employees
- Employees Left
- Attrition Rate %
- Avg Monthly Income
- Overtime Attrition Rate %
- Retention Rate %
- Dashboard Title (dynamic)
