# Superstore Sales and Profit Analysis

## Project Overview

This project analyzes Superstore sales data to understand overall business performance, profitability, regional contribution, customer performance, product performance, and the relationship between discounts and profit.

An interactive Excel dashboard was created using Pivot Tables, calculated fields, slicers, and data visualizations to make the analysis easier to explore and support data-driven decision-making.

## Business Problem

Superstore management needs a clear way to monitor sales and profitability across different regions, categories, sub-categories, customers, and products.

The purpose of this project is to identify:

- Sales and profit trends over time
- Top-performing product categories
- Regional sales and profit contribution
- Most valuable customers
- Top-selling products
- The relationship between discounts and profitability
- Shipping performance

## Dataset

The dataset contains transactional Superstore sales data, including information about:

- Order Date
- Ship Date
- Ship Mode
- Customer Information
- Customer Segment
- City and State
- Region
- Product Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

The original dataset was cleaned and structured before performing the analysis.

## Data Preparation

Additional fields were created in the cleaned dataset to support the analysis, including:

- Year
- Month
- Month Name
- Quarter
- Shipping Days
- Shipping Speed Category
- Profit Margin %
- Profit Category
- Discount Category
- Order Value Category

## Key Performance Indicators

The analysis includes the following KPIs:

- **Total Sales:** $2.30M
- **Total Profit:** $286.40K
- **Total Orders:** 9,994
- **Profit Margin:** 12.47%
- **Average Order Value:** calculated from total sales and orders
- **Average Shipping Days:** 3.96 days

## Analysis Performed

### 1. Sales Trend Over Time

Sales were analyzed by year to identify changes in business performance.

| Year | Sales |
|------|------:|
| 2014 | $484.25K |
| 2015 | $470.53K |
| 2016 | $609.21K |
| 2017 | $733.22K |

The analysis shows strong sales growth in the later years, with 2017 generating the highest sales.

### 2. Sales and Profit by Category

The three major product categories were compared based on sales and profit:

- Furniture
- Office Supplies
- Technology

Technology generated the highest sales and also contributed the highest profit among the three categories.

### 3. Sales and Profit by Region

Regional performance was analyzed across:

- Central
- East
- South
- West

The West region generated the highest sales and profit, followed by the East region.

### 4. Profit by Sub-Category

Profitability was analyzed at the sub-category level to identify products contributing positively or negatively to overall profit.

Some sub-categories generated negative profit, highlighting areas where pricing, discounting, or product strategy may need further attention.

### 5. Top 5 Products by Sales

The analysis identifies the five products generating the highest sales:

1. Canon imageCLASS 2200 Advanced Copier
2. Cisco TelePresence System EX90 Videoconferencing Unit
3. Fellowes PB500 Electric Punch Plastic Comb Binding Machine
4. GBC DocuBind TL300 Electric Binding System
5. HON 5400 Series Task Chairs for Big and Tall

### 6. Top 5 Customers

The analysis also identifies the top customers based on sales contribution.

The top customers include:

- Sean Miller
- Raymond Buch
- Tamara Chand
- Tom Ashbrook
- Adrian Barton

### 7. Discount vs Profit Analysis

The relationship between discount levels and profitability was analyzed.

The analysis shows that discounted orders do not necessarily result in higher profits. In particular, the high-discount category recorded a negative overall profit, while orders without discounts generated substantially higher profit.

This highlights the importance of managing discounts carefully.

### 8. Shipping Performance

Shipping performance was analyzed using shipping days and shipping speed categories.

The average shipping time across the dataset was approximately **3.96 days**.

## Dashboard

An interactive Excel dashboard was developed using:

- Pivot Tables
- Pivot-based charts
- Slicers
- Calculated fields
- KPI cards
- Report connections
- Data visualization

The dashboard allows users to filter the analysis by dimensions such as region, category, and customer segment.

## Tools & Techniques

**Microsoft Excel**

Techniques used:

- Data cleaning
- Excel Tables
- Calculated fields
- Pivot Tables
- Pivot Charts
- Slicers
- Date grouping
- KPI calculations
- Profit margin analysis
- Average Order Value (AOV)
- Conditional categorization
- Dashboard design

## Key Insights

- Technology was the highest-performing product category by sales.
- The West region generated the highest regional sales and profit.
- Sales increased significantly from 2014 to 2017.
- A small group of products contributed a significant amount of sales.
- Some sub-categories generated negative profit despite contributing to sales.
- High discounts were associated with negative overall profit in the analysis.
- Orders without discounts generated substantially higher profit.
- Average shipping time was approximately 3.96 days.

## Recommendations

Based on the analysis:

- Review discount strategies, especially high-discount orders.
- Focus on high-performing Technology products and profitable sub-categories.
- Investigate loss-making sub-categories such as Tables and Bookcases.
- Study the practices of high-performing regions and replicate successful strategies where appropriate.
- Continue monitoring sales and profit trends through the interactive dashboard.
- Use customer and product-level analysis to support targeted sales strategies.

## Project Files

- `Superstore_Sales_Profit_Analysis.xlsx` — Complete Excel analysis and dashboard
- `README.md` — Project documentation

## Data Source

Dataset sourced from Kaggle:

Superstore Sales Data Analysis
