## SA Food Delivery Sales Performance Analysis
Live Dashboard Screenshot: https://github.com/Sophie256A/Food-Delivery-Sales-Analysis/blob/main/Food%20Delivery%20Screenshot.png
Tool:Power BI|Power Query|DAX

## Project Overview
This project analyzes the October sales performance of SA food delivery company. The goal was to transform raw delivery data into an interactive dashboard that provides actionable business insights on revenue, customers, and operational performance.


## Business Problem
Management wanted answers to:
 Why October sales had declined?
 How are customers paying?
 What is the daily revenue trend and Average Order Value?
 How do Weather, Restaurant Type, Age Group, and Day affect sales?


## Tools & Skills Used
**Power BI Desktop:** Data Cleaning (Power Query), Data Modeling, DAX, Dashboard Design
**DAX Measures Created:** Total Revenue, Total Orders, Total Customers, Avg. Order Value
**Data Visualization:** KPI Cards, Bar Chart, Donut Chart, Line Chart, Slicers


## My Process
Data Cleaning and preparation(Power Query
Removed duplicates and nulls
Standardized City and Restaurant_Type fields
Created Age Group buckets (18-24, 25-34, 35-44, 45-54, 55+)
Converted Order_Date to proper date format for daily trend analysis

Data Modeling & Dax 
DAX
Total Revenue = SUM(Orders[Revenue])
Total Order = COUNT(Orders[Order_ID])
Total Customers = DISTINCTCOUNT(Orders[Customer_ID])
Avg. Order Value = DIVIDE([Total Revenue], [Total Order], 0)

Dashboard Development:
Designed a one-page interactive dashboard with 4 KPI cards, slicers for Weather, Restaurant_Type, Age Group, and Day, and 4 key visuals.

## Key Insights from Dashboard

KPIs for October:
Total Revenue: $1.9MTotal Orders: 50KTotal Customers: 5KAvg. Order Value: $37.481. City Performance:
City A is the dominant market with 19.9K orders (40% of total), followed by City B (14.9K). City D is the lowest with only 5.0K orders - needs attention.
2. Payment Method:
43.2% of customers (4K) prefer Digital Wallet / Card, 32% use Cash on Delivery (3K), and 24.7% use other methods. Shows high digital adoption.
3. Top Restaurants:
RES 0001 is the top performer generating $0.29M revenue alone, almost double of RES 0004 ($0.14M). Top 5 restaurants drive 32% of total revenue.
4. Daily Trend:
Revenue fluctuates between $59.4K - $65K+. Lowest revenue on Day 15 ($59.4K) and Day 3 ($60.1K). Revenue spikes after Day 18, indicating strong month-end performance.

## Recommendation

For City D: Launch targeted promotions and add more restaurant partners to increase order volume. For Meal Package Upselling: With an AOV of $37.48, introduce combo packages to push AOV to $45. Bundle top restaurants with high-margin items. For Payment: Promote digital payment discounts to reduce COD operational costs since 43% already use it. For Inventory: Partner closely with RES_0001 and RES_0004 to ensure availability during peak days. Revenue will grow by 30%

## Food-Delivery-Sales-Analysis
This repo contains a beginner friendly Food Delivery Sales Analysis done in  Power BI


