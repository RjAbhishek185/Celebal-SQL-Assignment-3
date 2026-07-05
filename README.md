# Celebal Technologies Internship – SQL Assignment 3

## Overview

This repository contains my Week 3 SQL assignment completed as part of the **Data Engineering Internship at Celebal Technologies**.

The assignment focuses on analyzing the **Sample Superstore** dataset using advanced SQL concepts such as **Subqueries**, **Common Table Expressions (CTEs)**, and **Window Functions**. The objective was to solve practical business problems by writing efficient SQL queries and extracting meaningful insights from the data.

---

## Objectives

- Import the Superstore dataset into MySQL.
- Create separate **Customers**, **Orders**, and **Products** tables from the raw dataset.
- Insert data using `SELECT DISTINCT`.
- Apply Subqueries, CTEs, and Window Functions to answer business-related questions.
- Generate customer sales insights through SQL analysis.

---

## Technologies Used

- MySQL 8.0
- MySQL Workbench
- SQL
- GitHub

---

## Dataset

The project uses the **Sample Superstore** dataset, which contains information about customer orders, products, sales, discounts, profits, shipping details, and regional data.

---

## Repository Structure

```
Celebal-SQL-Assignment-3
│
├── Query.sql
├── Sample - Superstore.csv
├── README.md
└── screenshots/
```

---

## Tasks Performed

### Database Setup

- Imported the Sample Superstore dataset.
- Created separate **Customers**, **Orders**, and **Products** tables.
- Populated the tables using `SELECT DISTINCT`.

### SQL Analysis

Implemented SQL queries to:

- Find orders with sales greater than the average sales.
- Retrieve the highest sales order for each customer.
- Calculate total sales for every customer using CTEs.
- Identify customers whose sales are above the overall average.
- Rank customers based on total sales using Window Functions.
- Assign row numbers to orders within each customer.
- Display the top three customers by total sales.
- Build a final query combining **JOIN**, **CTE**, and **Window Functions**.

### Customer Sales Insights

The project also answers the following business questions:

- Who are the top 5 customers?
- Who are the bottom 5 customers?
- Which customers placed only one order?
- Which customers have above-average sales?
- What is the highest order value for each customer?

---

## Key Learnings

Working on this assignment helped me strengthen my understanding of:

- SQL Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- Data aggregation techniques
- Analytical SQL queries
- Solving business problems using SQL

---

## Business Insights

- A relatively small group of customers contributes a significant share of total sales.
- Customer ranking makes it easier to identify high-value customers for loyalty programs.
- Customers with only one purchase represent potential opportunities for retention campaigns.
- Above-average spending customers can be targeted with personalized offers.
- Analyzing the highest order value per customer provides useful insights into purchasing behavior.

---

## Author

**Abhishek Raj**

B.Tech Computer Science Engineering  
DIT University, Dehradun

Data Engineering Intern  
Celebal Technologies
