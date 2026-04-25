# 🛒 Retail Sales Performance Analysis 2024
# Dashboard powered by Pareto-based Sales Intelligence
# Period: This Week
----
# Table of Contents
----
- [Analysis Overview](#analysis-overview)
- [Objective](#objective)
- [Data Source](#data-source)
- [Preparation Tools](#preparation-tools)
- [Data Processing](#data-processing)
- [Skills Demonstrated](#skills-demonstrated)
- [Insights For This Week Period](#insights-for-this-week-period)
- [Recommendations](#recommendations)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)
- [Dashboard Interaction](https://app.powerbi.com/groups/9fb15e56-0513-49f1-b8ba-bf62189bd04c/reports/d831b4cb-c540-4014-bc3c-772e7fadfb14/d06b28e503e04ebad1a0?experience=power-bi)
----

## Analysis Overview

This project presents a comprehensive Retail Sales Performance Analysis for Delight's Store, examining weekly sales data through the lens of the Pareto Principle (80/20 Rule). The analysis explores revenue concentration across multiple dimensions including product categories, subcategories, individual products, sales personnel, customers, regions, and states, to surface actionable intelligence for strategic decision-making.
By applying Pareto-based Pareto charts alongside revenue trend lines and threshold indicators, the analysis pinpoints which segments drive the most value and which require targeted intervention. The result is a dynamic, filterable Power BI dashboard that empowers stakeholders to make data-driven decisions with precision and confidence.

----

## Objective
The primary objectives of this analysis are:

- Identify revenue concentration: Determine which categories, products, customers, sales persons, regions and states generate the majority of total revenue.
- Apply the Pareto Principle: Use the 80/20 rule to segment high-impact contributors from low-impact ones across all dimensions.
- Track weekly performance: Monitor revenue trends, order volumes, profit margins and customer activity for the current week versus the prior week.
- Enable data-driven prioritization: Provide leadership with clear visual evidence of where to concentrate resources, marketing spend and sales effort.
- Surface underperformance: Highlight low-performing states, products and salespeople so targeted recovery strategies can be deployed.
  
----

## Data Source
----
- Source Type: Internal Retail Transaction Database
- Period Covered: This Week (Dec 24 – Dec 30)
- Total Revenue: $5,148,133.00
- This Week Revenue: $96,541 (1.88% of Total Revenue)
- Total Orders (This Week): 42
- Total Customers (This Week): 42
- Dimensions Covered: Category, Subcategory, Product, Customer, Sales Person, Region and State
- Metrics Tracked: Revenue, Profit, Orders and Pareto %

The dataset includes transactional records segmented by geography (12 US states, 4 regions), product taxonomy (5 categories, multiple subcategories and SKUs), customer profiles and sales representative assignments. Order status data captures fulfilment pipeline stages: Delivered, On Way, Awaiting Confirmation and New.
  
----

## Preparation Tools
----
The following tools were used across the data preparation, modelling and visualisation pipeline:
- Power BI Desktop: Primary dashboard development, DAX calculations and interactive visualisations.
- Microsoft Excel: Initial data exploration, cleaning and pre-processing.
- Power Query: ETL (Extract, Transform, Load) operations within Power BI
- DAX (Data Analysis Expressions): Custom measures for Pareto %, Revenue, Profit, WoW comparisons and KPI indicators
- GitHub: Version control, portfolio hosting and documentation.

![Screenshot](/images/Screenshot%20191712.png)

----

## Data Processing
----
The data processing workflow followed a structured ETL and modelling approach:
# Data Extraction & Loading: 
Raw transactional data was extracted from the retail database and loaded into Power BI via Power Query. 
Tables loaded include: Sales, Products, Customers, Geography, SalesPerson.

# Data Cleaning & Transformation: 
- Removed duplicate and null transaction records.
- Standardised date formats and ensured consistent fiscal week definitions.
- Validated geographic mappings (State → Region).
- Resolved inconsistencies in customer and sales representative name fields.
- Created Period table called ThisPeriod.
  
![Screenshot](/images/Screenshot%20200722.png)

# Data Modeling:
- Implemented a flat table with Sales as the fact table.
- Configured bi-directional and single-directional filters as appropriate.
- Created one to many relationship between the fact table and the date table.

![Screenshot](/images/Screenshot%20200832.png)

----

## Skills Demonstrated
----
- Data Analysis: Pareto Analysis, Trend Analysis, Comparative Analysis (WoW) and Concentration Analysis.
- Business Intelligence: KPI design, executive dashboard development, multi-dimensional drill-through.
- DAX & Power Query: Custom measures, cumulative calculations and time intelligence.
- Data Visualisation: Pareto combo charts, KPI cards, donut charts, line trend charts and order status bar charts.
- Storytelling with Data: Translating complex sales data into clear, decision-ready narratives.
- Data Modelling: Relationship management, filter context control.
- Critical Thinking: Identifying revenue drivers, flagging underperformers and formulating strategic recommendations.
- Documentation: Professional GitHub README writing and structured portfolio presentation.
----

## Insights For This Week Period

----

# KPI Overview:

----

![Screenshot](/images/Screenshot%20201001.png)

The KPI cards shows the following:
- Total Revenue this week: $97K (+13.8% vs. last week)
- Total Profit this week: $26K (+10.7% vs. last week)
- Total Orders: 42
- Total Customers: 42

Revenue for this week ($96,541) represents 1.88% of the total revenue ($5,148,133).

----

Revenue Trend

----

![Screenshot](/images/Screenshot%20200859.png)

The line graph shows the following:
- A day-by-day breakdown table (Dec 24–30) comparing each day's revenue against the weekly daily average of $13,792
- Identification of the Dec 24 spike (~$27K, nearly double the average) driven by pre-Christmas demand
- Explanation of the Dec 25–27 dip (post-Christmas lull pattern)
- Recognition of the steady recovery from Dec 28–30, rising back above average by Dec 30

The chart shows a V-shaped holiday retail cycle which positions the store's outlook positively for the coming week

----
# Pareto-based Performance Analysis
----

# Sales Performance by Category

![Screenshot](/images/Screenshot%20101022.png)

The clustered bar chart shows that South region continues to lead in sales, while the North shows promising growth potential.

Key Takeaway:
- The West have a strong performance improvement
- The South needs consistent regional leader
- There is an emerging growth opportunity in the North
- The East sales is stable but underperforming

----

Product-wise Sales Breakdown

----

![Screenshot](/images/Screenshot%20101007.png)

The column chart shows that monitor category has the highest growth, making it a key revenue driver in 2024.

Key Takeaway:
Headphones sustained market demand from 2023-2024
Laptop improved slightly upward from 2023-2024
Monitor sold the highest
Mouse	needs renewed marketing
Printer maintains a consistent sales.

----

## Recommendations

----

- Focus on Monitors & Headphones: These products show the strongest revenue potential.
- Boost North Region Sales: Implement targeted marketing campaigns or discounts to capitalize on its growing trend.
- Monitor Cost Efficiency: While profit increased by 34%, cost rose by 11%; cost optimization can further enhance margins.
- Address Seasonal Dips: Investigate reasons for May and December declines to maintain steady revenue performance.
----

## Dashboard

![Screenshot](/images/Screenshot%20114621.png)

----

## Conclusion
This dashboard provides a clear and interactive visualization of how business performance evolved from 2023 to 2024. It empowers decision-makers to identify profitable regions, track sales growth, and plan future strategies based on data-driven insights.


Connect with Me

Delight Amadi
📧 Nobledelight7@gmail.com
💼 Delight Amadi
