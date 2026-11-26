# E-Commerce Sales Analysis | Power BI

## Project Overview
An interactive E-Commerce Sales Dashboard built using Microsoft Power BI to analyze sales performance, profitability, customer behavior, and product trends.

## Tools & Technologies
- Power BI
- Power Query
- DAX
- Microsoft Excel

## Dataset
- 50,000 transaction records
- Sales, Profit, Cost, Quantity and Unit Price
- Product and Category
- Customer and Customer Segment
- State and City
- Payment Mode
- Order Date

## Dashboard Features
- Total Sales and Total Profit KPIs
- Total Orders and Customer KPIs
- Profit Margin Analysis
- State-wise Sales Analysis
- City-wise Product Quantity Analysis
- Target vs Actual Sales and Profit
- Payment Mode Analysis
- Interactive Year and Quarter Slicers
- Top 5 Products by Sales Revenue

## Key DAX Measures

```dax
Total Sales = SUM('New file'[Sales])

Total Profit = SUM('New file'[Profit])

Total Quantity = SUM('New file'[Quantity])

Total Orders = DISTINCTCOUNT('New file'[OrderID])

Total Customers = DISTINCTCOUNT('New file'[CustomerID])

Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)
```

## Skills Demonstrated
- Data Cleaning and Transformation
- Power Query
- DAX Calculations
- KPI Development
- Data Visualization
- Interactive Dashboard Development
- Business Intelligence

## Project Objective
To transform raw e-commerce transaction data into meaningful business insights and support data-driven decision-making.

## Author
Created as a Data Analytics portfolio project using Power BI.
