# Amazon_Product_Sales_Analysis

## Introduction

This project aims to analyze Amazon product sales data using Python. The analysis includes determining the best year and month for sales, identifying brands and product categories with the highest and lowest sales, and visualizing various aspects of the sales data. The primary tools used for this analysis are Pandas, Numpy, Matplotlib, and Seaborn.

## Objective

The main objectives of this project are:
- To identify the year with the highest sales.
- To determine the month with the best sales.
- To find the brands with the most and least sales.
- To identify the product categories with the highest and lowest sales.
- To visualize the distribution of sales and top-performing products.

## Dataset

The dataset used in this project contains information about Amazon product sales. The key attributes in the dataset include:
- `Year`: The year in which the sales occurred.
- `Month`: The month in which the sales occurred.
- `Brand`: The brand of the product.
- `Category`: The category of the product.
- `Sales`: The sales figures for the product.
- `Ratings`: The customer ratings for the product.

## Methodology

### Data Import and Cleaning
- The dataset is imported using the `read_csv()` function from Pandas.
- Basic data cleaning steps, such as handling missing values and correcting data types, are performed.

### Data Analysis
The following analyses are conducted using Pandas and Numpy:
- **Best Year of Sales**: Grouping sales data by year to identify the year with the highest sales.
- **Best Month of Sales**: Grouping sales data by month to determine the best-performing month.
- **Brands with Most and Least Sales**: Grouping sales data by brand to find the brands with the highest and lowest sales.
- **Top 3 Products**: Identifying the top 3 products based on sales figures.
- **Category-wise Sales**: Analyzing sales data by product category to find the highest and lowest selling categories.

### Data Visualization
Matplotlib and Seaborn are used for visualizing the results:
- **Year-wise Sales**: A bar plot showing sales figures for each year.
- **Month-wise Sales**: A bar plot showing sales figures for each month.
- **Top Brands**: A bar plot displaying the brands with the most and least sales.
- **Category-wise Sales**: A bar plot illustrating sales figures for different product categories.
- **Sales Distribution**: Various plots (e.g., histograms, box plots) showing the distribution of sales data.
- **Top 3 Products**: A bar plot highlighting the top 3 products by sales.

## Results and Conclusions

The analysis led to the following conclusions:

1. **Best Year of Sales**:
   - The year 2015 had the best sales.

2. **Best Month of Sales**:
   - The month of January had the best sales.

3. **Brands with Most Sales**:
   - Bose and Logitech sold the most.

4. **Brands with Least Sales**:
   - The brand EINCAR sold the least, followed closely by DURAGADGET.

5. **Category with Most Sales**:
   - The category of Headphones sold the most.

6. **Category with Least Sales**:
   - The category of Security and Surveillance sold the least.

## Tools and Libraries Used

- **Pandas**: For data manipulation and analysis.
- **Numpy**: For numerical operations.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For statistical data visualization.



This README file provides an overview of the project, including the objectives, dataset description, methodology, and key results. For detailed code and further analysis, refer to the project repository.
