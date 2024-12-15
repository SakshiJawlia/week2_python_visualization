# Data Engineering Case Study: Workflow Automation

## Overview
This project demonstrates data cleaning, transformation, and visualization for a sales dataset. 

## Dataset
The dataset contains sales information for different products across regions. It includes columns such as `Date`, `Region`, `Product`, `Sales`, `Profit`, `Quantity`, and `Rating`.

## Process
1. **Data Cleaning:**
   - Handled null values by replacing them with the mean.
   - Removed negative sales values.
2. **Data Transformation:**
   - Added a `Sales Category` column based on sales thresholds.
   - Aggregated data to calculate total sales and average profit by region and product.
3. **Visualization:**
   - Bar chart: Total sales by region.
   - Scatter plot: Relationship between sales and profit.
