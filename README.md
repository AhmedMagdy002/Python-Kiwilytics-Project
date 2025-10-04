# Python-Kiwilytics-Project
## 📌 Project Overview
This project analyzes a dataset of customer orders and product sales for **Kiwilytics**.  
The goal is to provide quick insights for the marketing team by cleaning the data, filling in missing values, calculating revenue, and visualizing key patterns.


## 🚀 Workflow
1. **Load Data**  
   - Load the CSV file into a pandas DataFrame.
   - Print dataset shape, info, and descriptive statistics.

2. **Data Cleaning**  
   - Check for missing values.
   - Fill missing `unit_price` values with the average price for each product.

3. **Feature Engineering**  
   - Create a new column `total_price = quantity × unit_price`.

4. **Analysis & Insights**
   - Calculate **total revenue**.
   - Identify the **top product** by total quantity sold.
   - Identify the **top customer** by total spending.

5. **Visualization**
   - Bar chart of **top 5 products by quantity sold**.
   - Bar chart of **top 5 customers by spending**.

6. **Validation**
   - Check for invalid (zero or negative) quantities or prices.

## ✅ Key Insights
- Total revenue generated across all orders.  
- Best-selling product (by quantity).  
- Highest-spending customer.  
- Visual patterns that help marketing target top customers and promote best-selling products.

## 📊 Example Visualizations
- **Top 5 Products by Quantity Sold**
- **Top 5 Customers by Spending**
