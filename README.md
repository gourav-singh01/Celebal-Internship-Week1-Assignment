# Celebal Technologies Internship Tasks

This repository contains my weekly assignment submissions for the Celebal Technologies Internship. All tasks are implemented using Python, Pandas, and SQLite inside Google Colab notebooks.

---

## 📁 Week 1: Data Exploration & Cleaning (Pandas)
* `assignment1.ipynb` - Notebook containing data profiling, handling missing values, and feature engineering.
* `Cleaned_Combined_dataset.csv` - The finalized clean e-commerce dataset.

### Tasks Completed
1. Loaded raw data to inspect data types, shapes, and structural traits.
2. Handled missing text values with descriptive placeholders and numerical blanks with median metrics.
3. Cleaned and dropped duplicate records.
4. Formatted string price columns into floats and engineered a custom total_amount metric (price * quantity).
5. Filtered the dataset to extract high-rated items (rating > 4.0).

---

## 📁 Week 2: E-Commerce Sales Database Analysis (SQL)
* `Assignment2.ipynb` - Initial project task focusing on loading data, profiling schema structures, and basic aggregates using the superstore dataset.
* `SQL_Task2_Week2.ipynb` - Detailed task notebook addressing all 27 business queries, constraint tests, and transaction workflows from the PDF sheet.
* `cleaned_superstore.csv` - The formatted, clean output dataset used during execution.

### Tasks Completed
1. Structured relational tables (customers, products, orders, order_items) with primary keys, foreign keys, and CHECK constraints.
2. Applied data filtering using WHERE clauses across specific categories.
3. Computed group-level aggregates (SUM, AVG, COUNT, MIN, MAX) for categories and order statuses.
4. Performed multi-table INNER and LEFT JOIN operations to track customer histories.
5. Implemented conditional tracking blocks using CASE logic.
6. Modeled a secure ACID-compliant SQL transaction with explicit BEGIN, COMMIT, and ROLLBACK handling.

---

## 📁 Week 3: Advanced SQL Analytics & Insights
* `SQL_Assignment_Week3.ipynb` - Notebook containing the primary written coding tasks, advanced joins, and structural queries.
* `SQL_Task_Week3.ipynb` - Notebook implementing the specific multi-table normalization schema and mini-project queries from the PDF task sheet.

### Tasks Completed (Relational Schema & Advanced Queries)
1. **Data Normalization:** Separated the raw superstore dataset into three structured relational tables (`customers`, `products`, and `orders`) using `SELECT DISTINCT` to eliminate data duplication.
2. **Subqueries:** Wrote query blocks to isolate orders with sales above the company average and to extract the maximum transaction value recorded for every unique customer.
3. **Common Table Expressions (CTEs):** Used CTEs to aggregate total sales per user profile and combined them with subqueries to filter customers outperforming the average spending benchmark.
4. **Window Functions:** Applied `RANK()` over customer metrics to sort the entire user base by total sales, and used `ROW_NUMBER() OVER (PARTITION BY...)` to sequentially number every transaction within each customer account.
5. **Integrated Query Matrix:** Combined a JOIN, a CTE, and `DENSE_RANK()` into a single final script to print a leaderboard of the top 10 highest-spending customers.

### 📊 Mini Project: Customer Sales Insights
Resolved targeted e-commerce business inquiries directly from the assignment PDF guidelines:
* Identified the top 5 and bottom 5 customers by sales revenue.
* Filtered and extracted inactive accounts that registered exactly 1 single order.
* Found all customer accounts tracking above-average sales totals.
* Discovered the maximum individual order value associated with each unique customer.
