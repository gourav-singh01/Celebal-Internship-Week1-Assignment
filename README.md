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
