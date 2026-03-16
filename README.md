# SQL Customer Behavior Analysis (PostgreSQL)

## Project Overview
This project analyzes customer purchasing behavior using SQL to extract business insights from transactional sales data. The goal was to identify key revenue drivers, understand customer segments, evaluate regional performance, and analyze the impact of discounts on profitability.

The analysis was conducted using PostgreSQL and demonstrates core data analytics skills including data exploration, aggregations, window functions, and business insight generation.

## Tools & Technologies
- PostgreSQL
- SQL
- Data Analysis
- Relational Databases
- Data Aggregation
- Window Functions

## Dataset
The dataset used in this project is the Superstore Sales dataset, which contains transactional data for a retail company.

The dataset includes information such as:
- Orders
- Customers
- Products
- Sales
- Profit
- Discounts
- Geographic regions
- Customer segments

## Project Objectives
The analysis aims to answer key business questions:

- Which customers generate the most revenue?
- Which regions drive the most sales?
- Which product categories are the most profitable?
- How do discounts impact profitability?
- What customer segments contribute the most revenue?

## Database Structure

The primary table used for analysis:

sales


Columns include:

- order_id
- order_date
- ship_date
- customer_id
- customer_name
- segment
- country
- city
- state
- region
- product_id
- category
- sub_category
- product_name
- sales
- quantity
- discount
- profit

## SQL Analysis Performed

The project includes multiple SQL analyses such as:

- Total revenue and profit calculations
- Revenue by geographic region
- Sales performance by product category
- Customer lifetime value analysis
- Customer purchase frequency
- Discount impact on profitability
- Monthly sales trends
- Customer revenue ranking using window functions

