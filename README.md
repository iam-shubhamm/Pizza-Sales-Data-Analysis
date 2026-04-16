🍕 Pizza Sales Analysis Dashboard

NOTE:

        This dashboard was created using Power BI. As I do not have a business account required
        for online deployment, I  have included screenshots below to showcase the dashboard.

📌 Project Summary

        The Pizza Sales Analysis Dashboard is a business intelligence project developed using MS
        SQL Server and Power BI. It focuses on analyzing sales data to uncover meaningful insights
        related to revenue generation, customer behavior, and product performance.
                              This dashboard enables stakeholders to make data-driven decisions  by 
        visualizing key metrics and trends.

🎯 Business Problem

        Pizza businesses generate large volumes of sales data daily, but without proper analysis,
        it becomes difficult to:

                * Identify top-performing products
                * Understand customer ordering patterns
                * Track revenue growth over time
                * Optimize product offerings

        👉 This project solves these problems using data analytics and visualization.

🛠️ Tools & Technologies Used

        * MS SQL Server → Data extraction, cleaning, and transformation
        * Power BI → Data visualization and dashboard creation
        * SQL → Writing queries for analysis

🔄 Project Workflow

        1️⃣ Data Collection
                * Imported pizza sales dataset into **SQL Server**
        2️⃣ Data Cleaning & Transformation
               *  Removed null/duplicate values
               *  Standardized columns
               *  Prepared dataset for analysis
        3️⃣ Data Analysis (SQL)
                * Calculated total revenue, orders, and quantities
                * Analyzed sales by category, size, and time

        4️⃣ Dashboard Development (Power BI)
                * Built interactive visuals and KPI cards
                * Added slicers for dynamic filtering
                * Designed user-friendly layout

📊 Dashboard Features

        🔹 KPI Metrics
                * 💰 Total Revenue
                * 🧾 Total Orders
                * 🍕 Total Pizzas Sold
                * 📉 Average Order Value
                * 📦 Average Pizzas per Order
        🔹 Sales Analysis
                * 📅 Daily Order Trends
                * 📆 Monthly Order Trends
                * 🕒 Peak Sales Hours
        🔹 Product Performance
                * 🥇 Best-Selling Pizzas (Revenue, Quantity, Orders)
                * 📉 Worst-Selling Pizzas
                * 📊 Category-wise Sales Analysis
                * 📦 Size-wise Sales Distribution
        🔹 Interactive Features
                * 🎯 Filters for Pizza Category
                * 📅 Date Range Slicer
                * 🔍 Drill-down analysis

📷 Dashboard Preview

📊 Sales Insights
        <img width="1132" height="605" alt="image" src="https://github.com/user-attachments/assets/1883a5dd-4a9a-48cf-a3f1-b13ff6567bfb" />

⭐ Best & Worst Sellers
        <img width="1129" height="604" alt="image" src="https://github.com/user-attachments/assets/eb32a024-9fdc-42de-a6eb-99691bcecbe7" />

        
🔍 Key Insights Derived

        * 📌 Sales peak on **Friday and Saturday evenings**
        * 📌 **July and January** generate the highest revenue
        * 📌 **Classic category pizzas** dominate total sales
        * 📌 **Large-size pizzas** are most preferred by customers
        * 📌 A small group of pizzas contributes to the majority of revenue (Pareto principle)

📁 Project Structure

        pizza-sales-dashboard/
        │
        ├── pizza-sales-analysis-dashboard.pbix
        ├── pizza_sales_data.csv
        ├── pizza-sales-sql-queries.sql
        ├── README.md
        └── images/

📥 How to Run This Project

        1. Clone or download this repository
        2. Open `.pbix` file in **Power BI Desktop**
        3. Explore visuals and interact with filters

💼 Use Case

        This dashboard can be used by:
                * Business owners to track performance
                * Analysts to identify trends
                * Managers to make strategic decisions


