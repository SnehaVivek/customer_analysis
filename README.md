# customer_analysis

## Description
An end-to-end data analytics project leveraging Python for data cleaning, SQL for querying and analysis, and Power BI for visualization. The dashboard tracks customer demographics, sales performance, revenue trends, subscription status, and key KPIs to support data-driven decisions.

# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer shopping behavior using Python, PostgreSQL, and Power BI. The objective is to uncover insights into customer demographics, purchasing patterns, subscription behavior, and category-wise sales performance. The project follows a complete data analytics workflow, including data cleaning, exploratory data analysis (EDA), SQL-based analysis, and dashboard development.

## Dataset
The dataset contains 3,900 customer records and 18 attributes related to shopping behavior, including:
* Customer ID
* Age
* Gender
* Item Purchased
* Category
* Purchase Amount (USD)
* Location
* Size
* Color
* Season
* Review Rating
* Subscription Status
* Shipping Type
* Discount Applied
* Promo Code Used
* Previous Purchases
* Payment Method
* Frequency of Purchases

## Tools & Technologies
* Python (Pandas, NumPy)
* Matplotlib & Seaborn
* PostgreSQL
* Power BI
* Jupyter Notebook

## Project Workflow

### Data Cleaning & Preprocessing

* Loaded the dataset using Pandas.
* Checked data types and summary statistics.
* Identified and handled missing values.
* Standardized column names for analysis.
* Created customer age segments (Young, Adult, Middle-aged, Senior).
* Prepared the dataset for SQL and dashboard reporting.

### Exploratory Data Analysis (EDA)

Performed analysis to understand:
* Customer demographics
* Purchase behavior across categories
* Review rating distribution
* Subscription trends
* Revenue contribution by customer segment
* Shopping preferences and purchase frequency

### SQL Analysis (PostgreSQL)

The cleaned dataset was imported into PostgreSQL for business analysis. SQL queries were used to:
* Calculate category-wise revenue
* Analyze customer subscription behavior
* Evaluate sales performance by age group
* Generate KPI metrics
* Identify high-performing customer segments

### Dashboard Development

An interactive Power BI dashboard was developed to visualize:
* Total Customers
* Average Purchase Amount
* Average Review Rating
* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Sales by Age Group
* Subscription Status Distribution

The dashboard also includes dynamic filters for:
* Subscription Status
* Gender
* Product Category
* Shipping Type

## Key Insights

* Clothing generated the highest revenue and sales among all categories.
* Young customers contributed the highest overall revenue.
* A significant portion of customers were non-subscribers.
* Customer purchasing behavior varied across age groups and product categories.
* Review ratings remained relatively consistent across product categories.

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── SQL Queries/
├── Power BI Dashboard/
├── Images/
└── README.md
```

## Results

The project demonstrates how Python, PostgreSQL, and Power BI can be combined to transform raw transactional data into actionable business insights. The findings can help businesses improve customer segmentation, optimize product strategies, and support data-driven decision-making.

## Author

Sneha Vivek

Skills Demonstrated: Data Cleaning, Exploratory Data Analysis, PostgreSQL, SQL Querying, Data Visualization, Business Intelligence, Dashboard Development, and Customer Analytics.
