# Retail Sales Performance Analysis (2023)

## Project Overview
This project analyses a retail sales dataset containing 1,000 transactions from 2023. The objective was to explore sales performance, identify revenue trends, understand customer segments, and develop business recommendations.

I used Google Sheets for data cleaning and exploratory analysis, followed by Tableau Public to build an interactive dashboard.

## Tools Used
- Google Sheets – Data cleaning, calculations and exploratory data analysis
- Tableau Public – Data visualisation and dashboard development

## Business Questions
- Which product categories generate the most revenue?
- How does revenue change throughout the year?
- Which customer age groups contribute the most revenue?
- Is revenue distributed differently across genders?

## Key Findings

### 1. Revenue by Product Category
- Electronics generated the highest revenue at $156,905.
- Clothing generated $155,580.
- Beauty generated $143,515.
- Revenue was relatively evenly distributed across the three categories.

### 2. Monthly Revenue Trends
- May recorded the highest monthly revenue at $53,150.
- September recorded the lowest monthly revenue at $23,620.
- September also had fewer transactions than May (65 compared with 105).

This suggests that both transaction volume and average transaction value may have contributed to the difference. The dataset does not establish the cause of the monthly variation.

### 3. Customer Age Groups
- Customers aged 46–55 generated the highest revenue at $100,690.
- Customers aged 26–35 followed with $98,480.
- Customers aged 56–65 generated the lowest revenue at $80,410.

### 4. Revenue by Gender
- Female customers generated $232,840.
- Male customers generated $223,160.

Revenue was relatively balanced between the two groups.

## Business Recommendations
- **Product categories:** Investigate product-level sales and margins to understand why Electronics leads revenue and whether the difference is commercially significant.
- **Clothing:** Clothing recorded the highest unit sales (894) but the lowest revenue per unit ($174.03). Explore product mix, bundles and upselling opportunities.
- **Monthly performance:** Investigate the reasons behind September's lower revenue and transaction volume. Review promotions, seasonality and product availability before deciding on any changes.
- **Customer segments:** Explore marketing campaigns tailored to the 46–55 and 26–35 age groups, while testing whether different customer segments respond to different offers.

## Data Cleaning and Methodology
- Reviewed the dataset for missing values.
- Checked transaction ID uniqueness.
- Created age brackets to group customers into five age ranges.
- Calculated total revenue, transaction counts, revenue by category and revenue by customer segment.
- Used monthly aggregation to identify revenue trends.
- Built charts in Tableau Public to communicate the findings.

## Dataset Limitations
- The dataset contains 1,000 transactions and is an educational retail sales dataset.
- It does not include individual product names, costs, profit margins, discounts or marketing campaign data.
- It does not establish why revenue changes between months.
- Customer income and occupation are not available, so purchasing power cannot be inferred.
- Findings describe this dataset and should not automatically be generalised to all retail businesses.

## Dashboard
[View the interactive Tableau Public dashboard](https://public.tableau.com:9443/views/Retailsalesperformancedashboard_17948027710890/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Project Summary
This project provided practical experience in data cleaning, exploratory data analysis, business interpretation and dashboard development. It demonstrates how spreadsheet analysis and data visualisation can be combined to identify patterns and communicate business insights.
