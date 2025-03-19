# Online Retail Data Analytics

## Overview
Online Retail Data Analytics is an end-to-end project that extracts actionable insights from the UCI Online Retail dataset. The project implements a comprehensive data pipeline—covering data cleaning, feature engineering, sales analysis, visualization, RFM segmentation, and customer churn analysis—to drive data-driven business decisions.

## Features
- **Data Cleaning & ETL**
  - Load and process the dataset using Pandas.
  - Clean over 500K transactions by handling missing values, merging product descriptions, and filtering out invalid entries.
  - Achieve 98% data integrity.

- **Sales Analysis & Visualization**
  - Analyze monthly sales trends and the top 5 countries by total sales using Matplotlib.
  - Uncover a 30% seasonal sales surge.
  - Visualize revenue contributions with both absolute and percentage-based bar charts.

- **Customer Segmentation & Churn Analysis**
  - Implement RFM segmentation (Recency, Frequency, Monetary) to categorize customers.
  - Conduct churn analysis based on 90+ days of inactivity, targeting a 10% improvement in customer retention.

## Technologies
- Python
- Pandas
- Matplotlib
- Openpyxl

## Installation
1. **Dataset Setup:**
   - Download the Online Retail dataset in CSV format from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/static/public/352/online+retail.zip).
   - Save the file as `Online_Retail.csv` in the project directory.

2. **Install Required Packages:**
   ```bash
   pip install openpyxl pandas matplotlib
   
**Pipeline Overview**

**Data Loading:**
Reads the CSV file (with latin1 encoding) to display initial records and dataset information.

**Data Cleaning:**
Handles missing values, merges product descriptions, and removes invalid quantity/price entries.

**Feature Engineering:**
Creates new columns such as TotalSales (calculated as Quantity × UnitPrice) and extracts the Month from InvoiceDate.

**Visualization:**
Generates plots to illustrate monthly sales trends, country-wise revenue distribution (absolute and percentage contributions), and product-wise sales performance.

**Customer Analysis:**
Applies RFM segmentation and churn analysis to identify high-value and at-risk customers.

Metrics & Insights
500K+ Transactions Processed
98% Data Integrity Achieved
30% Seasonal Sales Surge Identified
10% Improvement in Customer Retention Targeted
