# SQL-superstore-analysis-project
SQL analysis on superstore database
Superstore Retail Sales Analysis

Overview

A SQL project using PostgreSQL to analyse 9,994 retail sales records from the Sample Superstore dataset.

The goal was to practise newly learnt SQL and identify trends in revenue, profit and sales performance.

Tools and Skills

PostgreSQL and pgAdmin 4

SELECT, WHERE, GROUP BY, ORDER BY

SUM, AVG, COUNT, HAVING

INNER JOIN and CASE WHEN

Common Table Expressions (CTEs)

RANK() window function

Data cleaning and validation

Key Findings

Total sales: $2,297,201.07

Total profit: $286,397.02

Units sold: 37,873

Highest-revenue state: California

Highest-revenue and profit category: Technology


How to Run

Download the Sample Superstore CSV dataset (nine-column version). here: https://www.mathewkanalytics.com/datasets/superstore-sales

Create a PostgreSQL database, then paste and run database_setup

In pgAdmin, right-click sales_raw (under schemas - superstore - tables), then import the superstore csv. Enable Header, and set delimiter to comma and encoding to UTF8. Ensure the selected column order matches the CSV.

Run data_quality_validation.

Run each query in sales_analysis to reproduce the analysis.

