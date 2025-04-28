# Airlines-Dashboard

## Problem Statement

This dashboard enables businesses to analyze sales performance, forecast future sales, identify sales drivers, and compare sales across different segments. It provides valuable insights that help decision-makers optimize their strategies, address 
Preview
Raw
Airlines-Dashboard
# Problem Statement
Companies need a smart way to track, forecast, and analyze sales performance beyond static reports.
Goal: Deliver a dynamic Power BI dashboard that enables real-time monitoring, predictive insights, and interactive exploration of sales data.

# Steps Followed
Data Connection: Connected to the sales database and ensured data refresh.

Data Cleaning:

Checked for missing or incorrect values.

Replaced null values in the Postal Code column with 0 to ensure data consistency.

Added a new calculated column for Delivery Days by calculating the difference between Order Date and Delivery Date.

# Data Modeling and DAX Calculations:

Established relationships between tables (Sales, Product, Region, etc.).

Created DAX measures:

Average Delivery Days = Average of the Delivery Days column.

Total Profit = Sum of the Profit column.

Total Discount = Sum of the Discount column.

Total Sales = Sum of the Sales column.

Dashboard Development:

Forecast Tab: Built predictive sales forecasts based on historical trends.

Decomposition Tree: Designed to uncover key drivers behind sales figures.

Comparison View: Developed to compare sales across regions, products, and periods.

Q+A Section: Enabled natural language querying for faster ad-hoc insights.

# Testing & Validation:

Verified the accuracy of new columns and DAX measures (Average Delivery Days, Total Profit, Discounts, Sales).

Confirmed forecast models were aligned with historical sales trends.

Ensured all visuals displayed correctly and dynamically.

# Key Features
Forecast Sales Performance

Analyze Sales Drivers (Decomposition)

Compare Sales Across Segments

Instant Insights via Q+A

Custom DAX Metrics for Delivery Days, Profit, Discounts, and Sales


# Business Impact
✅ Enables data-driven decision-making
✅ Predicts future trends for proactive planning
✅ Saves time via self-service analytics
✅ Enhances strategic focus on top-performing area
