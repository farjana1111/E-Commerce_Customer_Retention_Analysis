# E-Commerce_Customer_Retention_Analysis
Analyzed 541K+ online retail transactions using SQL and Python to understand customer buying patterns, repeat purchases, and sales trends. Used RFM analysis to identify valuable and at-risk customers, studied products frequently bought together, and suggested ways to improve customer retention and increase sales.

# Project Overview

This project analyzes online retail transaction data using SQL and Python to understand customer purchasing behavior, retention, and sales performance. The goal is to identify valuable customers, understand repeat-purchase patterns, and discover products frequently purchased together.

# Objectives

1.Analyze monthly revenue, orders, and customer activity.

2.Identify valuable and at-risk customers using RFM analysis.

3.Measure customer retention using cohort analysis.

4.Understand revenue concentration through Pareto analysis.

5.Identify product combinations for cross-selling opportunities.

6.Compare sales performance across countries.

# Tools & Technologies

SQL : Data cleaning, querying, and analysis.

Python: Pandas, NumPy, Matplotlib.

Git & GitHub: Version control and project documentation.

# Dataset

The project uses the Online Retail dataset from the UCI Machine Learning Repository.

Raw records: 541,909 transaction lines.

Data period: December 2010 – December 2011.

Currency: British Pounds (GBP).

Cleaned product records: 391,150.

Dataset Source – UCI Machine Learning Repository

# Project Workflow

Data Cleaning: Removed duplicate records, cancelled invoices, missing customer IDs, invalid quantities or prices, and non-product entries.

Monthly Sales Analysis: Calculated revenue, order counts, active customers, average order value, and month-over-month revenue changes.

Customer Retention: Used cohort analysis to track repeat purchases after customers' first observed purchase month.

RFM Segmentation: Grouped customers into segments such as Champions, Loyal, Needs Attention, and At Risk.

Revenue Concentration: Applied Pareto analysis to measure the contribution of high-spending customers.

Country Analysis: Compared customer counts, revenue, and average order values across markets.

Market Basket Analysis: Identified frequently purchased product combinations using support, confidence, and lift.

Data Visualization: Created charts to communicate customer and sales insights.

# Key Findings

1.Champions: Approximately 26% of customers contributed 67% of analyzed revenue.

2.Revenue Concentration: The top 20% of customers generated approximately 75% of revenue.

3.At-Risk Customers: Identified 290 high-value customers with approximately £592K in historical spend.

4.Customer Retention: Cohort analysis highlighted the challenge of encouraging new customers to make repeat purchases.

5.Product Associations: Identified frequently purchased product pairs that could support cross-selling and bundle recommendations.

6.Seasonality: September to November accounted for approximately 37% of the year's analyzed revenue.

# Business Recommendations

Develop targeted win-back campaigns for high-value customers who have not purchased recently.

Encourage first-time customers to place a second order.

Offer complementary product bundles based on purchasing patterns.

Strengthen retention efforts for high-value customer segments.

Plan inventory and staffing around seasonal sales trends.

# Visualizations

The project includes:

RFM customer segment comparison.

Monthly revenue trends.

Customer cohort retention heatmap.

Pareto revenue concentration chart.
