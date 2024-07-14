# E-Commerce-Sales-Analysis-in-Brazil
This repository contains an in-depth analysis of Target's e-commerce operations in Brazil from 2016 to 2018. The dataset, originally sourced from Kaggle and converted to Excel format, is uploaded to MySQL for efficient querying and data manipulation. The analysis is performed using Python in Jupyter Notebook, leveraging libraries like pandas, SQLAlchemy, and matplotlib for data processing and visualization.

Dataset Overview
The dataset covers 100,000 orders and includes detailed information on:

Order Status
Pricing
Payment and Shipping Performance
Customer Locations
Product Attributes
Customer Reviews
Files Included

The data is split into the following CSV files:

customers.csv
sellers.csv
order_items.csv
geolocation.csv
payments.csv
orders.csv
products.csv
Potential Use Cases
Analyzing this dataset provides insights into:

Order processing
Pricing strategies
Payment and shipping efficiency
Customer demographics
Product characteristics
Customer satisfaction
These insights are invaluable for enhancing strategic decision-making.

Queries and Analysis
The analysis is divided into three levels: Basic, Intermediate, and Advanced.

Basic Queries
1) List all unique cities where customers are located.
2) Count the number of orders placed in 2017.
3) Find the total sales per category.
4) Calculate the percentage of orders that were paid in installments.
5) Count the number of customers from each state.
   
Intermediate Queries
1) Calculate the number of orders per month in 2018.
2) Find the average number of products per order, grouped by customer city.
3) Calculate the percentage of total revenue contributed by each product category.
4) Identify the correlation between product price and the number of times a product has been purchased.
5) Calculate the total revenue generated by each seller, and rank them by revenue.
   
Advanced Queries
1) Calculate the moving average of order values for each customer over their order history.
2) Calculate the cumulative sales per month for each year.
3) Calculate the year-over-year growth rate of total sales.
4) Calculate the retention rate of customers, defined as the percentage of customers who make another purchase within 6 months of their first purchase.
5) Identify the top 3 customers who spent the most money in each year.
Implementation

The implementation is done in Python using Jupyter Notebook. Here are the steps involved:
i) Data Import: Import the data from MySQL into pandas DataFrames using SQL queries.
ii) Data Cleaning: Handle missing values, data type conversions, and other preprocessing steps.
iii) Query Execution: Execute the specified queries using SQL and pandas operations.
iv) Visualization: Generate visualizations to illustrate key findings using matplotlib and seaborn.
v) Documentation: Provide detailed explanations and interpretations of the results.
