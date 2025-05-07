# Power BI Sales Dashboard

An end-to-end sales analytics dashboard to track sales performance against budget targets. The dashboard provides interactive insights across customer segments, products, and cities.

## Key Features

- Sales Overview with pie, line, and bar charts
- Product-level performance with gradient comparisons and monthly trends
- Customer-specific metrics with pivot tables and geographic breakdowns
- Sales vs. Budget tracking and seasonal trend analysis

## Technical Implementation

### Data Cleaning and Preparation (SQL)

- Renamed and combined columns
- Used `LEFT JOIN`, `CASE()`, and `ISNULL()` for data transformation
- Filtered datasets based on business reporting needs

### Data Modeling

- Structured data model using fact and dimension tables
- Linked Calendar, Customer, Product, InternetSales, and Budget tables

### Dashboard Development (Power BI)

- Integrated dynamic filtering by product, city, and timeframe
- Created visuals for top customers and products
- Visualized customer sales distribution on map
- Analyzed sales trends and performance over time

## Tools and Technologies

SQL  
Power BI  
DAX
Data Modeling  
Data Visualization
