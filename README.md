# E-Commerce Business Performance Analysis (SQL + Power BI)

Analyzed sales, profit, refunds, and product performance for an online toy store (Mar 2012 to Mar 2015). SQL (PostgreSQL) was used for the analysis, and Power BI for the dashboard.

## Dashboard (3 pages)

![Overview](1_overview.png)
![Sales Analysis](2_sales_analysis.png)
![Product Analysis](3_product_analysis.png)

## Data model
![Data model](4_data_model.png)

## What I did
- SQL (PostgreSQL): analyzed revenue, profit, refunds, and top products across 4 related tables using JOINs, aggregations, and date functions
- Power BI: built a 3-page dashboard (Overview, Sales, Product) on a 4-table data model, with DAX measures for revenue, orders, average order value, refunds, and profit

## Key findings
- About $2M revenue from 32K orders, with $85K in refunds (about 4% of revenue)
- The top product, The Original Mr. Fuzzy, generated about 60% of revenue and profit
- Orders peaked in 2014 at 16.9K
- The data runs from 19 Mar 2012 to 19 Mar 2015, so 2012 and 2015 are partial years

## Data
Four tables: products, orders, order items, and order item refunds (CSV files in this repository). The SQL file creates the tables and loads the data into PostgreSQL.

## Files
- `ecommerce_analysis.sql`: SQL queries
- `Ecommerce_Data.pbix`: Power BI file
- `Orders.csv`, `Order_items.csv`, `Order_item_refunds.csv`, `Products.csv`: data
- `1_overview.png` to `4_data_model.png`: dashboard pages and data model

## Tools
PostgreSQL, SQL, Power BI, DAX
