## bookstore-sql-analytics-project
SQL practice project with real-world analytical questions, JOINs, subqueries, CTEs, and multi-table analysis using a bookstore dataset.
<br><br>
### About the Project

This project contains a complete set of intermediate and advanced SQL questions that I practiced to sharpen my analytical thinking and database problem-solving skills.
It is designed for learners who want to move beyond basic SELECT queries and work with real analysis-style SQL challenges using multi-table data.

The goal is simple:
👉 Practice real business queries
👉 Think like a data analyst
👉 Level up SQL skills through hands-on problem solving

I am sharing the entire question list so others can practice the same challenges.

### 🗂️ Database Schema
The project uses 3 connected tables:

customers (customer_id, name, email, phone, city, country)
     |
     |-- orders (order_id, customer_id, book_id, order_date, quantity, total_amount)
               |
               |-- books (book_id, title, author, genre, published_year, price, stock)

### 🎯 What’s Included

This repository contains:
File	Description
questions_list.txt	All intermediate + advanced SQL questions
sample_queries.sql	My solutions and SQL queries
books.csv	Books dataset
customers.csv	Customer dataset
orders.csv	Orders dataset
ERD / Schema image (optional)	Database relationship diagram

### 🧠 Skills Practiced
This project includes SQL concepts such as:
Multi-table JOINs
Aggregations and group analysis
Conditional filters
Subqueries (correlated + non-correlated)
CTEs for structured logic
Date/time functions
Calculations (revenue, totals, averages)
Inventory / stock logic
Case-based analytical questions

These questions simulate the kind of tasks asked in real analytics roles.

### 📝 Sample Question Types
Some examples from the question list:
Find the top-selling books and calculate total revenue
Identify customers with the highest purchase frequency
Check low-stock books based on recent orders
Analyze genre-wise sales performance
Find monthly/weekly order trends
Use CTEs to rank books by revenue
Create customer segmentation based on spending

### 🚀 How to Use This Project

Clone or download this repository
Import the CSV files into your SQL database
Open questions_list.txt
Try solving each question on your own
Compare with my queries in sample_queries.sql
Modify or extend the dataset to create more challenges
This project is perfect for self-learning, portfolio work, or interview preparation.

### 📊 Why This Project Matters

Hands-on SQL projects help build real problem-solving experience.
Working on analytical questions like these is key to:

✔ strengthening data thinking
✔ preparing for analytics interviews
✔ building a solid portfolio
✔ improving query-writing confidence
