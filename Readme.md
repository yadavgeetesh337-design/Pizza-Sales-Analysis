# 🍕 Pizza Sales Analysis & Dashboard

## 📌 Project Overview
This project analyzes sales data of a pizza restaurant to uncover key business insights such as revenue, order trends, best-selling pizzas, and category-wise performance.

The workflow followed in this project:
1. **SQL Server** – Used SQL Server for data cleaning and writing all analytical queries to calculate KPIs and trends.
2. **MS Excel** – Imported the cleaned data from SQL Server into Excel and built pivot tables, charts, and an interactive dashboard on top of it.

Both the SQL queries and the Excel dashboard produce the **same results**, so the SQL file can be used to verify/reproduce the numbers shown on the dashboard.
## 🗂️ Dataset
The dataset used is `pizza_sales`, containing order-level details of a pizza store, including:

| Column | Description |
|---|---|
| pizza_id | Unique ID for each pizza item in an order |
| order_id | Unique ID for each order |
| pizza_name_id | Identifier for pizza name/size combination |
| quantity | Quantity of pizza ordered |
| order_date | Date of the order |
| order_time | Time of the order |
| unit_price | Price per pizza |
| total_price | Total price (unit_price × quantity) |
| pizza_size | Size of the pizza (S/M/L/XL) |
| pizza_category | Category of pizza (Classic, Veggie, Supreme, Chicken) |
| pizza_ingredients | Ingredients used |
| pizza_name | Name of the pizza |
## 🧮 KPIs Calculated
- **Total Revenue**
- **Average Order Value**
- **Total Pizzas Sold**
- **Total Orders**
- **Average Pizzas per Order**
## 📊 Analysis Performed
- **Daily Trend for Total Orders** 
- **Hourly Trend for Total Orders**
- **% of Sales by Pizza Category** 
- **% of Sales by Pizza Size** 
- **Total Pizzas Sold by Category**
- **Top 5 Best Sellers** 
- **Top/Bottom 5 by Month**
## 🛠️ Tools & Process
- **SQL Server (T-SQL)**
  - Data cleaning of raw pizza sales data
  - Writing analytical queries for KPIs and trend analysis (`SQLQuery1.sql`)
- **Microsoft Excel**
  - Imported the cleaned data from SQL Server
  - Built Pivot Tables and Pivot Charts on the imported data
  - Designed an interactive dashboard using the pivot tables/charts
## ▶️ How to Use
1. Load the raw pizza sales data into SQL Server.
2. Run the cleaning steps and queries in `SQLQuery1.sql` to clean the data and get KPI/trend values.
3. Import the cleaned data into Excel and open `Pizza_sales_dashboard.xlsx` to view the interactive dashboard (pivot tables & charts).
4. Cross-check: The numbers from the SQL output should match the values shown on the Excel dashboard.

