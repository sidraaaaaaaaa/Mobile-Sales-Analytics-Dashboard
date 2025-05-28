# Mobile-Sales-Analytics-Dashboard
 I built an interactive Power BI dashboard for analyzing mobile phone sales data across geographies, channels, and customer demographics to derive actionable business insights.
**ey skills used:** 

Data Cleaning, Data Modeling, DAX, Data Visualization.

**Details on skills applied:**

This project was built using a semi-structured dataset from Onyx Data. The dataset included a flat sales table, along with `Dim_Product` and `Dim_Location` tables. However, it didn’t include a proper Date table or Customer table, which meant I had to handle data modeling from the ground up.

I started by loading the data into Power Query and doing some exploratory analysis to get a sense of the structure and spot any issues. From there, I cleaned and transformed the data directly in Power BI to make it usable for reporting.

Since key dimensions were missing, I created a custom Date table and Customer table to set up a proper star schema by linking the fact and dimension tables through physical relationships. This structure made it possible to write reliable DAX measures and use time-based functions for insights like monthly trends, running totals, and cumulative revenue.

Everything I built, from data modeling and DAX calculations to visuals, was designed to answer real stakeholder questions, such as:

- Which phone models are top performers?
- Which countries and sales channels drive the most revenue?
- What sales trends emerge over time?

For the first time in my journey, I used a **Pareto Chart** to apply the 80/20 rule and discovered that **just 7 mobile models contribute over 70% of total sales**. This insight confirmed that a small portion of the product lineup delivers the majority of business value. As a result, stakeholders were able to **prioritize inventory, marketing, and distribution strategies** around these top performers and **reallocate resources** from low-impact models.
