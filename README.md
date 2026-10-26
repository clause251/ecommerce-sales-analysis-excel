# Wholesale Customer Spending Analysis

## Project Overview

This project analyzes wholesale customer spending patterns using Microsoft Excel. It explores how spending varies across product categories, sales channels, and regions to identify useful business insights.

The project demonstrates a beginner-friendly data analytics workflow, from data cleaning and spreadsheet formulas to summary analysis and dashboard visualization.

## Business Questions

- Which product categories account for the highest total spending?
- How do average spending patterns differ between Horeca and Retail customers?
- Which region has the highest average spending per customer?
- Which product categories are more important to each sales channel?

## Tools Used

- **Microsoft Excel:** Data cleaning, formulas, summary tables, and charts
- **GitHub:** Project documentation and portfolio hosting

## Dataset

**Source:** UCI Machine Learning Repository — Wholesale Customers

https://archive.ics.uci.edu/dataset/292/wholesale+customers

The dataset contains 440 customer records and six annual product-category spending variables:

- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicassen

It also includes customer channel and region codes.

**Important:** This dataset represents annual customer spending, not individual transactions or monthly sales.

## Project Workflow

1. **Data collection:** Obtained the dataset from the UCI Machine Learning Repository.
2. **Data preparation:** Preserved the original data and created a separate cleaned-data sheet.
3. **Data cleaning:** Checked for missing values, data types, invalid codes, negative values, duplicate records, and potential outliers.
4. **Feature creation:** Converted channel and region codes into readable labels and calculated total annual spending per customer.
5. **Exploratory analysis:** Compared spending totals and averages by product category, channel, and region.
6. **Dashboard creation:** Built KPI cards and charts to communicate the main findings.

## Key Findings

- **Fresh:** The category with the highest total spending across the dataset.
- **Retail vs. Horeca:** Retail customers have higher average total spending per customer than Horeca customers.
- **Regional comparison:** The Other region has the highest average total spending per customer among the three regions.
- **Channel preferences:** Horeca customers have higher average spending on Fresh and Frozen, while Retail customers have higher averages for Milk, Grocery, Detergents_Paper, and Delicassen.

These findings describe patterns in this dataset and do not establish the causes behind customer spending behavior.

## Project Files

- `Wholesale_Customer_Analysis.xlsx` — Excel workbook containing the raw data, cleaned data, analysis, dashboard, and cleaning log.
- `dashboard.png` — Screenshot of the completed dashboard.

## Skills Demonstrated

- Data cleaning and validation
- Excel formulas and calculated columns
- Aggregation and descriptive analysis
- Comparative analysis
- Data visualization and dashboard design
- Business insight communication
- Project documentation using GitHub

## Data Attribution

Dataset: *Wholesale customers*, UCI Machine Learning Repository.

The dataset is distributed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. Please refer to the original dataset page for attribution and license details.

## Future Improvements

- Add pivot tables and interactive filters.
- Explore customer segments using clustering.
- Recreate the dashboard in Power BI.
- Compare findings across customer segments and product categories.
