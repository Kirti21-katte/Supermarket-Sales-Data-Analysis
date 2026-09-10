# Supermarket Sales Data Analysis
This project analyzes supermarket sales data using Python, Excel, and Power BI.

## 1. Project Overview

This project analyzes supermarket sales transaction data to understand sales performance, customer behavior, product-line performance, payment preferences, and sales trends. The project uses Python for data preparation, exploratory data analysis, and visualization, along with Power BI for creating an interactive dashboard.

The analysis helps identify high-performing and low-performing areas and provides data-driven business recommendations for improving supermarket performance.

## 2. Problem Statement

Supermarkets generate a large amount of transaction data, but raw data alone does not clearly show important business patterns. The purpose of this project is to analyze supermarket sales data and identify useful information about product lines, cities, customers, payment methods, and sales trends.

The project aims to convert the raw transaction data into meaningful insights that can support better business decisions related to sales, inventory, marketing, and customer engagement.

## 3. Dataset Description

**Dataset Name:** Supermarket Sales Dataset
**Domain:** Sales / Retail Analytics
**Number of Records:** 1,000
**Number of Columns:** 17
**Time Period:** January to March 2019

### Main Columns

* Invoice ID
* Branch
* City
* Customer type
* Gender
* Product line
* Unit price
* Quantity
* Tax 5%
* Total
* Date
* Time
* Payment
* Cost of goods sold
* Gross margin percentage
* Gross income
* Customer stratification rating

The dataset contains supermarket transaction records covering products, customers, sales amounts, payment methods, and customer ratings.

## 4. Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook / Google Colab
* Power BI
* Git
* GitHub

## 5. Data Cleaning Process

The dataset was inspected to understand its structure, columns, data types, missing values, and duplicate records.

The following data preparation steps were performed:

* Loaded the dataset using Pandas.
* Checked the number of rows and columns.
* Inspected all column names and data types.
* Checked for missing values.
* Checked for duplicate records.
* Checked for incorrect values in important numerical columns.
* Checked customer ratings for valid values.
* Converted the `Date` column into datetime format.
* Prepared the `Time` column for analysis.
* Saved the prepared dataset as `supermarket_sales_prepared.csv`.

The final dataset was prepared for further analysis and visualization.

## 6. Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the main characteristics, relationships, patterns, and trends in the supermarket sales data.

The analysis included:

* Descriptive statistics
* Data inspection
* Data cleaning checks
* Missing-value analysis
* Correlation analysis
* Product-line sales analysis
* City-wise sales analysis
* Monthly sales analysis
* Outlier detection using the IQR method

The EDA helped identify important sales patterns and relationships that were later used for visualization and dashboard creation.

## 7. Data Visualizations

Five meaningful visualizations were created using Python:

1. **Total Sales by Product Line** — Bar Chart
2. **Total Sales by City** — Bar Chart
3. **Monthly Sales Trend** — Line Chart
4. **Payment Method Distribution** — Pie Chart
5. **Unit Price vs Quantity** — Scatter Plot

These visualizations help compare sales performance, understand trends, examine payment preferences, and identify relationships between numerical variables.

## 8. Power BI Dashboard

An interactive Power BI dashboard was created using the Supermarket Sales dataset.

### KPI Cards

* Total Sales
* Total Gross Income
* Total Quantity Sold

### Dashboard Visualizations

* Total Sales by Product Line
* Total Sales by City
* Monthly Sales Trend
* Payment Method Distribution

### Dashboard Filters / Slicers

* City
* Product line
* Customer type

The dashboard provides an interactive view of important business metrics and allows users to filter the analysis according to different customer and sales categories.

## 9. Key Insights

Based on the EDA, visualizations, and Power BI dashboard, the following key insights were identified:

1. Food and Beverages is the highest-performing product line in terms of total sales, while Health and Beauty has comparatively lower sales.

2. Naypyitaw records the highest total sales among the three cities, while Mandalay records comparatively lower sales.

3. Monthly sales vary during the analyzed period, with January showing the highest sales and February showing the lowest sales.

4. E-wallet is the most frequently used payment method, showing strong customer preference for digital payments.

5. Sales performance differs across product lines, creating opportunities to focus marketing and promotional activities on lower-performing categories.

6. Quantity sold has a strong positive relationship with total sales, meaning that higher quantities purchased generally result in higher transaction values.

7. Member and Normal customers both contribute significantly to supermarket transactions.

## 10. Business Recommendations

Based on the identified insights, the following recommendations are proposed:

1. **Promote low-performing product lines:** Introduce targeted discounts, combo offers, and promotional campaigns for lower-performing categories such as Health and Beauty.

2. **Improve lower-performing city sales:** Analyze customer demand in Mandalay and use location-specific promotions and marketing campaigns to improve sales.

3. **Use sales trends for inventory planning:** Use historical monthly sales patterns to plan inventory and promotional activities according to customer demand.

4. **Support digital payment preferences:** Continue providing convenient E-wallet and other digital payment options and consider suitable digital-payment offers to improve customer engagement.

## 11. Conclusion

This project analyzed the Supermarket Sales dataset using Python and Power BI. The data was inspected and prepared before performing exploratory data analysis and creating meaningful visualizations.

The analysis identified important patterns in product-line performance, city-wise sales, monthly sales trends, payment methods, and customer behavior. The Power BI dashboard provides an interactive way to explore these business metrics.

The insights and recommendations from this project can help supermarket management make better decisions related to sales performance, inventory planning, marketing activities, and customer engagement.
