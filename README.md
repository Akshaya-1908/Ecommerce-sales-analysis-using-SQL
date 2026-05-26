# E-commerce sales analysis using SQL
MySQL project analyzing e-commerce sales data to generate business insights and performance metrics.
## Project Overview
This project analyzes an E-Commerce Product Sales dataset containing 1,000 records using MySQL.
The objective of this project is to explore the dataset, perform data quality checks, analyze sales performance, evaluate product ratings, examine inventory status, and generate meaningful business insights using SQL queries.

The analysis focuses on:
- Data Exploration
- Data Cleaning
- Sales Analysis
- Revenue Analysis
- Product Performance
- Category Performance

## Dataset Columns
- product_id
- product_name
- category
- price
- units_sold
- rating
- in_stock

## SQL Concepts Used
- SELECT
- WHERE
- GROUP BY
- ORDER BY
- LIMIT
- COUNT()
- SUM()
- AVG()
- ROUND()

## Key Analysis Performed
1. Total products count
2. Product categories analysis
3. Product count by category
4. Average price by category
5. Highest rated products
6. Top selling products
7. Revenue by product
8. Revenue by category
9. Stock availability analysis
10. Products with rating above 4

## Key Insights
- Electronics category contains the highest number of products.
- Electronics generated higher revenue than Fashion products.
- Laptop is the highest revenue-generating product.
- Laptop is one of the best-selling products in the dataset.
- Keyboard achieved the highest average customer rating.
- Most products have moderate customer ratings.
- Around 80% of products are available in stock,reflecting good inventory availability.
- Nearly 20% of products are currently out of stock,which could affect future sales if not replenished.
- The dataset contains no missing values.
- No duplicate product IDs were found.

## Project Structure
```text
Ecommerce-Sales-Analysis-SQL
│
├── ecommerce_analysis.sql
├── ecommerce_dataset.csv
├── README.md
│
└── screenshots
    ├── dataset_preview.png
    ├── total_products.png
    ├── categories_present.png
    ├── product_count_by_category.png
    ├── avg_price_by_category.png
    ├── highest_rated_products.png
    ├── top5_selling_products.png
    ├── avg_product_rating.png
    ├── revenue_by_category.png
    └── in_stock_product_count.png
```
## Tools Used
- MySQL Workbench
- SQL
- GitHub

