# E-commerce Sales Analysis

## Project Overview
This project focuses on analysing an e-commerce sales dataset using Python to identify revenue trends, top-performing products, and valuable customers. The goal is to understand sales performance and provide actionable business recommendations.

## Objectives
- Identify products generating the highest revenue.
- Analyse monthly sales trends and Month-over-Month (MoM) growth.
- Identify the most valuable customers.
- Examine customer purchasing frequency.
- Provide data-driven business recommendations.

## Dataset
The project uses the **Online Retail Dataset**, which contains transaction-level information.

Key columns:
- `InvoiceNo` – Invoice number
- `StockCode` – Product code
- `Description` – Product description
- `Quantity` – Quantity purchased
- `InvoiceDate` – Date and time of transaction
- `UnitPrice` – Price per unit
- `CustomerID` – Customer identification number
- `Country` – Customer's country

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed
1. **Data Cleaning:** Handled missing values, checked duplicates, and filtered cancelled transactions and invalid sales records.
2. **Feature Engineering:** Extracted year, month, month name, weekday, and quarter from the invoice date.
3. **Revenue Analysis:** Calculated revenue using Quantity × UnitPrice and identified top-performing products.
4. **Monthly Trend Analysis:** Analysed monthly revenue and Month-over-Month growth.
5. **Customer Analysis:** Identified high-value customers based on total spending and purchase frequency.
6. **Pareto Analysis:** Examined the revenue contribution of the top 10% of customers.

## Key Finding
The top 10% of customers contributed approximately **61.33% of total revenue**, highlighting the importance of customer retention and repeat purchases.

## Business Recommendations
- Introduce loyalty rewards for high-value customers.
- Provide personalised offers to encourage repeat purchases.
- Monitor monthly revenue trends to plan promotions.
- Focus on products that generate the highest revenue.
- Develop targeted marketing campaigns for valuable customer segments.

## Project Status
Completed – Exploratory Data Analysis (EDA).

