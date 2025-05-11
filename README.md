# blinkit_Sales_Analysis

## Table of Content

- Project Overview
- Project Goal
- Data Source
- Tools Used
- Data Cleaning and Preparation
- Data Analysis
- Findings / Results
- Recommendations
- Limitations
- References

## Project Overview

- This project involves a sales and customer behavior analysis for Blinkit, a leading online grocery delivery service. The dataset consists of grocery sales transactions across various outlets, including item details, outlet characteristics, and customer ratings.

## Project Goal

- The primary objective is to analyze Blinkit’s grocery sales data to uncover patterns, trends, and factors influencing sales. The insights derived will help improve inventory decisions, marketing strategies, and outlet performance.

## Data Source

- File: BlinkIT Grocery Data.xlsx

- Contents: 8,523 records across 12 columns related to item characteristics, outlet information, and sales performance.

- Columns include:

1. Item Type, Fat Content, Weight, Visibility

2. Outlet Type, Size, Location

3. Sales figures and Customer Ratings
   

## Tools Used

- Power BI: For building interactive dashboards and visual analytics.

- Microsoft Excel: For initial data handling and structure.
  

## Data Cleaning and Preparation

- Handled missing values in Item Weight (~17% missing).

- Normalized inconsistent values in Item Fat Content (e.g., "low fat", "Low Fat", "LF" unified).

- Verified data types and ensured numeric fields like Sales and Rating were correctly formatted.

- Removed outliers in Item Visibility to improve accuracy in visual trends.
  

## Data Analysis

- Sales Trends: Identified high and low-performing outlets by sales volume.

- Outlet Comparison: Analyzed outlet size, location, and type to understand impact on performance.

- Item Category Performance: Compared sales across item types (e.g., Dairy, Snacks, Beverages).

- Rating Impact: Studied how customer ratings influence sales volume.

- Year of Establishment: Analyzed outlet performance based on how long they’ve been operating.

-  KPI Dashboard Highlights (Total Sales, Average Rating, and Top-Selling Item Categories).


## Findings / Results

- Supermarket Type1 outlets showed the highest overall sales.

- Tier 1 cities contributed significantly more to revenue than Tier 2 or 3.

- Items with higher visibility and consistent ratings tend to sell better.

- Certain categories like Dairy and Snacks outperformed others in both volume and revenue.


## Recommendations

- Focus marketing efforts on high-performing categories and Tier 1 cities.

- Standardize item visibility through better online display and search optimization.

- Improve underperforming outlets through localized promotions or operational changes.

- Expand Supermarket Type1 model in new locations given its proven success.

- Enhance data collection for customer feedback to refine the rating system further.

  
## Limitations

- Missing data in Item Weight might slightly skew product-specific conclusions.

- Customer demographics and promotional data were not included.

- Sales influenced by seasonal trends were not distinguished in this dataset.


## References

- Data Source: BlinkIT Grocery Sales Dataset (internal)

- Tool: Microsoft Power BI for visualization

- Documentation: Blinkit Business Model and Market Reports

- Inspiration: Kaggle Big Mart dataset (similar structure)
