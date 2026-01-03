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

## Key Insights & Business Findings
- **Sales efficiency varies widely by store**: A small number of stores generate significantly higher average sales per square foot, showing that operational efficiency matters more than store size alone.
- **Holiday periods drive a disproportionate share of revenue**: Although holidays represent a limited number of weeks, they account for a materially higher percentage of total sales, highlighting the importance of holiday-focused planning.
- **Markdown spending shows diminishing returns**: Increased markdown activity does not always translate into higher sales, suggesting opportunities to optimize discount strategies rather than increase discount volume.
- **Sales are concentrated in a limited set of departments**: A small group of departments contributes a large share of total revenue, indicating where inventory, pricing, and promotional efforts should be prioritized.

## Interactive Version
- Due to GitHub file size limits, the Excel workbook is hosted externally:
https://1drv.ms/x/c/F6C2F4C1831A2F3D/IQD1ygXVQ2xgTbEq5qQFB1YCAatek8W4yWsh_6f0fzuGBrs?e=bYE4xh
