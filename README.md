# Chinook-Business-Analytics (SQL + Tableau)

## Overview

This project focuses on analyzing business performance using SQL and Tableau through the Chinook Database, a sample digital music store database. The project simulates a real-world Business Intelligence (BI) workflow by extracting insights from transactional data and presenting them through an interactive dashboard.

The analysis examines customer spending behavior, revenue trends, geographic sales performance, and product popularity to support data-driven decision-making.

---

## Dataset Information

This project uses the **Chinook Database**, a sample relational database designed for learning SQL, database management, and business intelligence concepts.

📌 Source: https://github.com/lerocha/chinook-database

The database simulates a digital media store and contains information about:

- Customers
- Invoices
- Invoice line items
- Music tracks
- Genres
- Artists
- Employees

The following tables were primarily used in this project:

- Customer
- Invoice
- InvoiceLine
- Track
- Genre

---

## Technologies Used

- SQL
- SQLite
- DB Browser for SQLite
- Tableau Public

---

## SQL Analysis

SQL was used to extract, aggregate, and analyze data from the database.

### SQL Concepts Applied

- SELECT statements
- INNER JOINs
- Aggregate functions (SUM, COUNT, AVG)
- GROUP BY
- ORDER BY
- Multi-table relational analysis

### Business Analyses Performed

- Total customer count
- Total revenue calculation
- Average order value (AOV)
- Customer revenue analysis
- Revenue by country
- Revenue by genre
- Product performance analysis

---

## Dashboard Components

### KPI Cards (Total Revenue, Total No. of Customers, Average Order Value)
### Revenue by Country
### Top 5 Genres by Revenue Share
### Top 10 Customers by Revenue
### Revenue trend

---

## Key Insights

### Revenue Performance

The Chinook music store generated approximately **$2,329** in total revenue from customer purchases.

### Customer Base

The database contains **59 customers**, providing a diverse customer base across multiple countries.

### Customer Value

A small group of customers contributes a disproportionately higher amount of revenue compared to the average customer, highlighting the importance of customer retention and relationship management.

### Geographic Performance

Revenue is concentrated in a few countries, indicating stronger market presence and customer engagement in those regions.

### Product Performance

The top-performing genres account for a significant portion of total revenue, suggesting clear customer preferences within the product catalog.

### Revenue Trends

Revenue fluctuates over time, with several noticeable peaks that may indicate periods of increased customer activity.

---

## Author

This project was built as a learning exercise in SQL and Business Intelligence, focusing on:

- SQL querying
- Relational database analysis
- Business analytics
- Dashboard development
- Data visualization using Tableau
