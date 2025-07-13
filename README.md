# 🍕 SQL Pizza Orders Data Analysis

This project involves analyzing a pizza restaurant's order data using SQL. It showcases skills in data cleaning, SQL querying, joining multiple tables, revenue analysis, and uncovering business insights. Excel was used in the initial data processing phase to prepare and import the data into the SQL database.

---

## 📂 Project Overview

- **Database Name**: `Pizzahut`
- **Main Tables**:
  - `orders`: Order-level data (order ID, date, time)
  - `orders_details`: Line-item level pizza data per order
  - `pizzas`: Pizza metadata including size and price
  - `pizza_types`: Pizza names and category information

---

## 🔄 End-to-End Flow

1. **Data Cleaning in Excel**  
   - Handled formatting, ensured column consistency, and removed anomalies in the raw CSVs.
   - Used Excel to structure the data before importing to SQL.

2. **Data Import to SQL**  
   - Loaded cleaned data into MySQL using SQL scripts and import tools.

3. **Relational Modeling & Table Creation**  
   - Created normalized tables using `CREATE TABLE` statements with primary keys and relationships.

4. **SQL Analysis**  
   - Ran advanced queries to answer real-world business questions using `JOINs`, `GROUP BY`, `ORDER BY`, `WINDOW FUNCTIONS`, and `AGGREGATIONS`.

---

## 📊 Business Questions Answered

| # | Question |
|----|----------|
| Q1 | How many total orders were placed? |
| Q2 | What is the total revenue from pizza sales? |
| Q3 | Which pizza is the most expensive? |
| Q4 | What is the most popular pizza size? |
| Q5 | Top 5 most ordered pizza types by quantity? |
| Q6 | What is the total quantity ordered by pizza category? |
| Q7 | What are the peak order hours during the day? |
| Q8 | How many pizzas are in each category? |
| Q9 | What is the average number of pizzas ordered per day? |
| Q10 | Which 3 pizzas generate the highest revenue? |
| Q11 | What percentage of revenue comes from each category? |
| Q12 | What does the cumulative revenue over time look like? |
| Q13 | Top 3 revenue-generating pizzas within each category? |

---

## 🛠️ Tools & Technologies

- **Excel** – Used for initial data cleaning and importing data to MySQL
- **SQL (MySQL-compatible)** – Data manipulation, joins, aggregations, and analytics
- **ETL Concepts** – Extract (Excel), Transform (cleaning), Load (SQL)
- **Window Functions** – For cumulative revenue and ranking

---

## 📌 Insights & Takeaways

- 🔸 Large pizzas are the most commonly ordered size  
- 🔸 Barbecue Chicken is the top revenue-generating pizza  
- 🔸 Most orders are placed between 12 PM – 1 PM  
- 🔸 Classic pizzas have the highest category sales  
- 🔸 Clear seasonal and daily trends visible in cumulative revenue  

---

## 📁 File Structure

- `pizza_orders_analysis.sql` → All SQL queries and logic  
- `README.md` → Project overview and documentation  
- `raw_data/` → Original and cleaned Excel files (if shared)

---

## 📬 Author

**Shejal Singh**  
📍 Pune, Maharashtra  
📧 [singhshejal899@gmail.com](mailto:singhshejal899@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/shejal-singh ) • [GitHub](https://bit.ly/Shejal-Singh)
