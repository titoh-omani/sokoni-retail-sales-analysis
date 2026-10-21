# Sokoni Retail Data Cleaning and Analysis

## Project Overview

This project focuses on cleaning, transforming, and analyzing retail transaction data for Sokoni Retail using Python. The goal is to improve data quality and generate useful business insights into sales, profits, product performance, payment methods, and customer satisfaction.

The project uses Pandas and NumPy to clean and prepare the dataset. Matplotlib is used to create visualizations, while Tableau is used to present business insights through an interactive dashboard.

## Tableau Dashboard

**Explore the interactive dashboard here:**

[View Sokoni Retail Dashboard on Tableau Public](https://public.tableau.com/app/profile/titus.omani/viz/Book1_17925948990120/Dashboard1?publish=yes)

The dashboard provides a visual overview of retail performance and helps users explore sales trends, branch performance, product profitability, and other business metrics.

## Project Objectives

- Inspect the retail dataset and identify data quality issues.
- Handle missing values and duplicate transactions.
- Standardize column names, text values, and data types.
- Validate and recalculate missing sales and profit values where possible.
- Create additional analytical columns, including profit margins, weekdays, and quarters.
- Analyze sales and profit trends across months, branches, and product categories.
- Examine payment methods, customer satisfaction, and product return rates.
- Develop visualizations to communicate findings.
- Prepare cleaned data for interactive reporting in Tableau.

## Tools and Technologies

- **Python:** Main programming language for data analysis.
- **Pandas:** Data cleaning, transformation, grouping, and aggregation.
- **NumPy:** Numerical calculations and data validation.
- **Matplotlib:** Creating charts and visualizing data.
- **Jupyter Notebook:** Interactive environment for data cleaning and analysis.
- **Tableau Public:** Building and sharing an interactive dashboard.

## Data Cleaning Process

1. Load and inspect the original retail dataset.
2. Standardize column names and remove unnecessary spaces from text values.
3. Identify and remove duplicate transactions using transaction IDs.
4. Convert dates to datetime format and standardize date-related fields.
5. Validate and standardize month information.
6. Handle missing sales and profit values using available transaction data.
7. Preserve missing customer satisfaction ratings rather than inventing values.
8. Check for invalid values and investigate potential outliers.
9. Create additional analytical columns, including profit margin percentage, weekday, and quarter.
10. Validate the cleaned dataset and export it for further analysis.

## Key Visualizations

The analysis includes the following visualizations:

1. **Monthly Sales and Profit Trend:** Examines changes in sales and profit over time.
2. **Sales and Profit by Branch:** Compares financial performance across retail branches.
3. **Profit by Product Category:** Examines profitability across product categories.
4. **Top 10 Products by Profit:** Identifies the products generating the highest profits.
5. **Payment Methods:** Explores customer payment preferences.
6. **Customer Satisfaction and Return Rate by Branch:** Compares customer ratings and product returns across branches.
7. **Sales Heatmap by Branch and Month:** Highlights sales patterns across branches and months.

## Key Skills Demonstrated

- Data cleaning and preprocessing
- Missing value handling
- Data type conversion
- Data validation and quality checks
- Exploratory data analysis
- Data aggregation using Pandas
- Data visualization
- Dashboard development and reporting
- Communicating business insights through data

## Project Files

- `sokoni_cleaning_and_analysis.ipynb`: Jupyter Notebook containing the data cleaning, analysis, and visualization workflow.
- `sokoni_retail_data.csv`: Original dataset used in the analysis.
- `sokoni_retail_cleaned.csv`: Cleaned dataset prepared for analysis and reporting.
- Tableau Public dashboard: [View the interactive dashboard](https://public.tableau.com/app/profile/titus.omani/viz/Book1_17925948990120/Dashboard1?publish=yes).

## Conclusion

This project demonstrates a complete data analysis workflow, from cleaning raw retail data to exploring business trends and presenting findings through an interactive Tableau dashboard. It showcases practical skills in Python, data preparation, exploratory data analysis, visualization, and business intelligence reporting.

The project highlights how data analysis can help businesses understand performance, identify patterns, and make informed decisions.
