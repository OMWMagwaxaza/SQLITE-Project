# SQLITE-Project

## Project Overview
This repository contains a SQL-based data analysis project using the Chinook Database, a sample database for a digital music store. As a Data Analyst, your role is to query the data and extract business insights to help improve sales performance and customer satisfaction.

## Scenario:
You work at a music store that tracks customers, invoices, sales agents, and music albums through a relational database. You’ve been tasked with running various SQL queries to support management in decision-making.

## Dataset Description
Name: Chinook Database
Format: SQLite (Chinook_Sqlite.sqlite)
Source: Chinook GitHub Repository

Tables Include:
- Customer, Invoice, InvoiceLine
- Employee, Genre, MediaType, Artist, Album, Track

## Technologies Used
- SQLite / .sqlite
- Python + sqlite3
- Jupyter Notebook

## Project Objectives
The project is divided into 4 sections:

### 1. Data Familiarization
- Q1: List all table names in the database.
- Q2: Display the first 5 rows of the Customer table.

### 2. Sales Analysis
- Q3: Total sales per country (descending order).
- Q4: Top 5 customers by total purchase amount.
- Q5: Most purchased genres (by number of purchases).

### 3. Employee & Customer Insights
- Q6: For each sales agent, show how many customers they manage and total customer sales.
- Q7: List customers who have not made any purchases.

#### 4. Advanced Querying
- Q8: Top 3 albums by revenue.
- Q9: Average invoice total per customer, sorted from highest to lowest.
