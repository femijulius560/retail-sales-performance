# retail-sales-performance

## Overview
End-to-end retail sales analysis built entirely in Microsoft Excel using Power Query, PivotTables, and dashboarding.
The project demonstrates a complete analytics workflow: data ingestion, cleaning, transformation, feature engineering, aggregation, and visualization — all within a single multi-sheet Excel workbook.
The dashboard is designed to support business decision-making by highlighting store performance, sales trends, holiday impact, and markdown effectiveness.

## Tools Used
- Microsoft Excel
- Power Query
- Pivot Tables & Charts
- Slicers

## Data
- Retail Dataset from Kaggle: https://www.kaggle.com/datasets/manjeetsingh/retaildataset/data 

## ETL & Data Preparation (Power Query)
- Imported all datasets using Power Query.
- Enforced correct data types (dates, numeric measures, logical flags).
- Replaced null markdown values with zero.
- Performed joins: Sales + Features (Store, Date) + Stores (Store).
- Retained only the final merged table as the analysis source.

## Feature Engineering
- Total Markdown: Sum of MarkDown1–5
- Time Attributes: Month Name, Year–Month
- Sales per Square Foot: Weekly_Sales ÷ Store Size

## Analysis & KPIs
- Total Sales
- Average Sales per Square Foot
- Total Markdown Spend
- Holiday Sales % of Total Revenue

## Visualizations
- Sales Trend Over Time (line chart)
- Top 10 Stores by Total Sales
- Top 10 Stores by Avg Sales per Sq Ft
- Top 10 Departments by Total Sales
- Holiday vs Non-Holiday Sales Share
- Markdown vs Sales by Holiday Type

## Slicers
- Year
- Store
- Holiday Type

## Dashboard Preview
screenshots/retail dashboard overview.png

## Interactive Version
- Due to GitHub file size limits, the Excel workbook is hosted externally:
https://1drv.ms/x/c/F6C2F4C1831A2F3D/IQD1ygXVQ2xgTbEq5qQFB1YCAatek8W4yWsh_6f0fzuGBrs?e=bYE4xh
