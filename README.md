# powerbi-sales-analysis
Sales variance analysis between iPhone 14 and iPhone 15 using Power BI (DAX + Power Query)
# iPhone 14 vs iPhone 15 Sales Variance Analysis

## Objective
This project analyzes sales performance of iPhone 14 and iPhone 15
using absolute variance and percentage variance to understand
product-wise sales movement across stores.

## Dataset
- dim_stores.csv – Store and country level details
- fact_sales_Iphone14.csv – Sales data for iPhone 14
- fact_sales_Iphone15.csv – Sales data for iPhone 15

## Data Model
- Star schema
- dim_stores connected to both fact tables via store_id

## Key Measures
- Total Sales – iPhone 14
- Total Sales – iPhone 15
- Absolute Sales Variance
- Sales Variance %

## Tools & Concepts Used
- Power BI
- DAX Measures
- Data Modeling
- Variance Analysis

## Output
Power BI dashboard showing comparative sales and variance metrics.
