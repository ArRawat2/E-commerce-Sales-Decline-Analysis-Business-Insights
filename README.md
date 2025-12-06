# E-Commerce Revenue Decline Analysis Dashboard

Power BI Project

## Overview

This project analyzes revenue decline, customer retention, inventory performance, and stock-out impact for an e-commerce business. The goal is to identify key issues affecting revenue and provide actionable insights using a multi-page Power BI dashboard supported by SQL-based data preparation.

## Key Objectives

* Understand quarterly revenue trends and revenue decline.
* Analyze customer behavior, retention, and revenue contribution.
* Evaluate inventory strength, stock-out impact, and lost revenue.
* Identify root causes and recommend data-driven business actions.

## Dataset

A custom dataset with over 50,000 rows was created, containing:

* Orders data
* Order items data
* Product details
* Customer profiles
* Inventory and stock-out logs

### SQL Usage

Basic SQL was used for:

* Initial dataset generation
* Data validation and record consistency checks
* Removing duplicates, fixing missing values, and ensuring referential integrity
* Preparing clean CSV outputs for Power BI import

These SQL operations ensured the dataset was structured, accurate, and ready for analysis.

## Dashboard Structure

### Page 1: Business Performance Overview

* Total Revenue, Completed Revenue, Q3 & Q4 Revenue
* Revenue Decline Percentage
* Stock-Out Percentage
* Completed Revenue Trend
* Category-wise Line Revenue
* Stock-Out Impact by Category
* City and Category Slicers

### Page 2: Customer Insights

* Active Customers
* Repeat Customers and Repeat Rate
* Orders Count
* Average Revenue per Customer
* Revenue Contribution by City
* Revenue Contribution by Age Group
* Customer Segmentation (New vs Repeat)

### Page 3: Inventory and Lost Revenue Analysis

* Stock-Out Products and Stock-Out Rate
* Average Inventory per Product
* Total Products
* Lost Revenue Estimate
* Stock-Out Impact by Category
* Orders Count vs Average Inventory by Category
* Lost Revenue Table (Brand-Level)

### Page 4: Strategic Insights and Recommendations

* Key Insights Identified from Data
* Root Cause Analysis
* Business Recommendations
* Estimated Business Impact

## Technologies Used

* Power BI Desktop
* DAX for calculated measures and KPIs
* Power Query for data transformation
* SQL for dataset preparation and cleaning
* Data modeling with star-schema relationships

## Key Outcomes

* Identified categories driving maximum revenue loss.
* Exposed inventory imbalance and forecasting gaps.
* Highlighted heavy dependency on repeat customers.
* Provided actionable recommendations to improve revenue recovery, inventory planning, and customer satisfaction.

## How to Use

1. Download the `.pbix` file from the repository.
2. Open with Power BI Desktop.
3. Explore each dashboard page using filters and slicers for interactive analysis.

