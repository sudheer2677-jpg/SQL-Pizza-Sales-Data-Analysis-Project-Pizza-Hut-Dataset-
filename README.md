🍕 SQL Pizza Sales Data Analysis | MySQL Project

(GitHub-Ready Detailed Description)

This project analyzes sales performance using a Pizza Hut dataset. The workflow includes data cleaning in Excel, database design, and advanced SQL queries to generate meaningful business insights such as revenue trends, top-selling pizzas, and customer purchase behavior.

📌 Project Overview

Cleaned the raw Pizza Hut sales dataset using Excel by removing duplicates, fixing inconsistent data types, and standardizing date/time formats.

Designed a normalized MySQL database schema with linked tables:

Orders

Order Details

Pizza Types

Pizza Categories

Executed advanced SQL queries to analyze sales trends, peak order times, most profitable items, and customer preferences.

Added indexes and optimized queries, resulting in faster execution and improved analytical performance.

🛠️ Tech Stack

SQL (MySQL)

Excel (initial data cleaning)

Database Normalization

Query Optimization / Indexing

🧹 Data Cleaning Steps

Removed duplicate records in Excel

Standardized date & time formats

Corrected inconsistent categorical values

Ensured numeric columns followed proper types

Exported the cleaned dataset for MySQL import

🗄️ Database Schema Highlights

Orders Table
Contains order IDs, dates, and times

Order Details Table
Connects orders with specific pizza items and quantities

Pizza Types Table
Describes pizza flavors and ingredients

Pizza Categories Table
Categorizes pizzas (e.g., Classic, Veggie, Supreme)

Designed using 1-to-many relationships for proper normalization and faster querying.

📊 Key SQL Concepts Used

JOINs (INNER, LEFT)

GROUP BY and HAVING

Aggregate functions (SUM, COUNT, AVG)

Common Table Expressions (CTEs)

Window functions (ROW_NUMBER, RANK)

Date & time functions

Indexing & query optimization

📈 Business Insights Extracted

Total revenue for the entire period

Top 5 best-selling pizzas

Category-wise performance (e.g., Classic vs Supreme)

Busiest order day & hour

Average order value

Revenue contribution by pizza size

Most profitable combinations of items

These insights support decisions on inventory, pricing, and menu optimization.

🚀 Performance Improvements

Added indexes on frequently filtered columns (e.g., OrderDate, PizzaTypeID)

Reduced query execution time by up to 20%

Improved slicing, filtering, and reporting performance for large datasets
