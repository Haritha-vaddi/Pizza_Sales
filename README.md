# Pizza_Sales
# 🍕 Pizza Sales Analysis Dashboard (MySQL + Power BI)

## Project Overview

The Pizza Sales Analysis Dashboard is an end-to-end Data Analytics project developed using **MySQL** and **Power BI**. The objective of this project is to analyze pizza sales performance, identify business trends, understand customer preferences, and generate actionable insights through interactive visualizations.

The project follows a complete analytics workflow, including:

* Data Import and Storage in MySQL
* Data Cleaning and Transformation
* SQL-Based Business Analysis
* Power BI Dashboard Development
* Business Insights and Reporting

---

# Business Problem Statement

The business wants to analyze pizza sales data to gain insights into overall performance, customer behavior, product popularity, and sales trends.

The goal is to answer key business questions related to revenue, orders, product performance, category contribution, and customer preferences.

---

# KPI Requirements

We need to analyze key indicators for our pizza sales data to gain insights into our business performance. Specifically, we want to calculate the following metrics:

### 1. Total Revenue

The sum of the total price of all pizza orders.

### 2. Average Order Value

The average amount spent per order, calculated by dividing the total revenue by the total number of orders.

### 3. Total Pizzas Sold

The sum of the quantities of all pizzas sold.

### 4. Total Orders

The total number of orders placed.

### 5. Average Pizzas Per Order

The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.

---

# Charts Requirement

We would like to visualize various aspects of our pizza sales data to gain insights and understand key trends.

### 1. Daily Trend for Total Orders

Create a bar chart that displays the daily trend of total orders over a specific time period. This chart will help identify patterns and fluctuations in order volumes on a daily basis.

### 2. Monthly Trend for Total Orders

Create a line chart that illustrates the monthly trend of total orders throughout the year. This chart will help identify peak months and periods of high order activity.

### 3. Percentage of Sales by Pizza Category

Create a pie chart that shows the distribution of sales across different pizza categories. This chart provides insights into the popularity of various pizza categories and their contribution to overall sales.

### 4. Percentage of Sales by Pizza Size

Generate a pie chart that represents the percentage of sales attributed to different pizza sizes. This chart helps understand customer preferences for pizza sizes and their impact on sales.

### 5. Total Pizzas Sold by Pizza Category

Create a funnel chart that presents the total number of pizzas sold for each pizza category. This chart allows comparison of sales performance across categories.

### 6. Top 5 Best Sellers by Revenue, Total Quantity and Total Orders

Create a bar chart highlighting the top 5 best-selling pizzas based on Revenue, Total Quantity Sold, and Total Orders. This chart helps identify the most popular pizza options.

### 7. Bottom 5 Best Sellers by Revenue, Total Quantity and Total Orders

Create a bar chart showcasing the bottom 5 worst-selling pizzas based on Revenue, Total Quantity Sold, and Total Orders. This chart helps identify underperforming or less popular pizza options.

---

# Tools & Technologies Used

* MySQL Server
* MySQL Workbench
* Power BI Desktop
* SQL
* DAX
* Power Query
* Data Modeling

---

# Database Information

### Database Name

`pizza_db`

### Table Name

`pizza_sales`

### Dataset Fields

* pizza_id
* order_id
* pizza_name_id
* quantity
* order_date
* order_time
* unit_price
* total_price
* pizza_size
* pizza_category
* pizza_ingredients
* pizza_name

---

# SQL Analysis Performed

The following SQL operations were performed during the project:

* Data Validation
* Data Cleaning
* Data Type Conversion
* Revenue Analysis
* Order Analysis
* Product Performance Analysis
* Category Analysis
* Daily Trend Analysis
* Monthly Trend Analysis
* Top 5 and Bottom 5 Product Analysis

---

# Dashboard Features

## KPI Cards

* Total Revenue
* Average Order Value
* Total Pizzas Sold
* Total Orders
* Average Pizzas Per Order

## Visualizations

* Daily Trend for Total Orders
* Monthly Trend for Total Orders
* Percentage of Sales by Pizza Category
* Percentage of Sales by Pizza Size
* Total Pizzas Sold by Pizza Category
* Top 5 Best Sellers by Revenue
* Top 5 Best Sellers by Quantity
* Top 5 Best Sellers by Orders
* Bottom 5 Best Sellers by Revenue
* Bottom 5 Best Sellers by Quantity
* Bottom 5 Best Sellers by Orders

## Interactive Filters

* Pizza Category
* Pizza Size
* Order Date

---

# Key Business Insights

* Identified the highest revenue-generating pizzas.
* Identified the lowest-performing pizzas.
* Analyzed customer preferences by pizza size.
* Measured category-wise sales contribution.
* Tracked daily and monthly order trends.
* Evaluated overall business performance using key KPIs.
* Identified best-selling and worst-selling pizza products.

---

# Project Workflow

```text
Dataset
   ↓
MySQL Database
   ↓
Data Cleaning & Transformation
   ↓
SQL Analysis
   ↓
Power BI Connection
   ↓
Data Modeling
   ↓
DAX Measures
   ↓
Dashboard Development
   ↓
Business Insights
```

---

# Learning Outcomes

Through this project, the following skills were applied and strengthened:

* SQL Query Writing
* Data Cleaning
* Data Transformation
* MySQL Database Management
* Power BI Dashboard Development
* DAX Calculations
* Data Modeling
* Data Visualization
* Business Analysis
* End-to-End Data Analytics Project Execution

---

# Conclusion

This project demonstrates an end-to-end data analytics workflow using MySQL and Power BI. The dashboard provides valuable insights into pizza sales performance, customer preferences, product popularity, and business trends. Through KPI analysis and interactive visualizations, the project supports data-driven decision-making and helps identify opportunities for business growth and operational improvement.
