
# Superstore Sales Analysis

## Introduction
This project involves performing a detailed analysis of the Superstore dataset to uncover insights related to sales, profit, and customer segments. The analysis is performed using Python and various data visualization techniques in a Jupyter notebook.

## Dataset Description
The dataset consists of sales data from a fictional superstore. It includes information about orders, products, customers, and regions. The columns in the dataset are:

- **Ship Mode**: The shipping mode used for the order.
- **Segment**: The customer segment (e.g., Consumer, Corporate, Home Office).
- **Country**: The country where the order was placed (all entries are 'United States').
- **City**: The city where the order was placed.
- **State**: The state where the order was placed.
- **Postal Code**: The postal code of the order.
- **Region**: The region where the order was placed.
- **Category**: The product category (e.g., Furniture, Office Supplies, Technology).
- **Sub-Category**: The product sub-category.
- **Sales**: The sales amount.
- **Quantity**: The quantity of items ordered.
- **Discount**: The discount applied to the order.
- **Profit**: The profit made from the order.

## Analysis Steps
The analysis performed in this project includes the following steps:
1. **Loading and Inspecting the Data**: Loading the dataset and displaying its structure.
2. **Basic Descriptive Statistics**: Calculating mean, median, and standard deviation of numeric columns, and summarizing categorical variables.
3. **Data Cleaning**: Handling missing values, correcting data types, and removing duplicates if any.
4. **Exploratory Data Analysis (EDA)**:
    - Visualizing the distribution of numerical features.
    - Visualizing categorical data using bar plots.
    - Analyzing relationships between different variables using scatter plots and correlation matrices.
5. **Segmentation Analysis**:
    - Geographic Segmentation: Analyzing sales and profit by region.
    - Category Segmentation: Analyzing sales and profit by product category and sub-category.
    - Customer Segment Analysis: Analyzing profit by customer segment.
6. **Advanced Analysis**: Identifying trends over time and performing additional
