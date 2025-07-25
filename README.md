# 📊 Zepto SQL Data Analysis Project

This project performs SQL-based data analysis on a sample dataset from Zepto, a quick commerce platform. The goal is to derive insights such as customer order behavior, top-performing items, and sales trends using structured queries and a provided CSV dataset.

---

## 📁 Files Included

- `zepto_v2.csv` – The dataset used for analysis. It contains customer orders and item-level details.
- `Zepto_SQL_data_analysis.sql` – SQL queries for analyzing the dataset and deriving key business insights.

---

## 🛠️ Technologies Used

- **Database:** PostgreSQL 
- **Tools:** pgAdmin
- **Language:** SQL

---

## 📌 Setup Instructions

### 1. Import the Data

To work with the dataset:

- Open your SQL client (e.g., pgAdmin ).
- Create a new database (e.g., `zepto_analysis`).
- Create a table and import `zepto_v2.csv`.

#### Sample Table Creation (PostgreSQL)
```sql
CREATE TABLE zepto_orders (
    order_id INT,
    user_id INT,
    order_time TIMESTAMP,
    item_name TEXT,
    quantity INT,
    price_per_unit FLOAT,
    total_price FLOAT
);
