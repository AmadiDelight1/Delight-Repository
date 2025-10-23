# SALES PERFORMANCE ANALYSIS USING EXCEL(2023-2024)
----
# Table of Contents
----
- [Analysis Overview](#analysis-overview)
- [Data Source](#data-source)
- [Preparation Tools](#preparation-tools)
- [Data Processing](#data-processing)
- [Skills Demonstrated](#skills-demonstrated)
- [Objective](#objective)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)
  
----

## Analysis Overview
This project presents a comparative sales performance analysis between 2023 and 2024, focusing on two major product categories Accessories and Electronics. The goal of this dashboard is to visualize how sales, profit, and product distribution have evolved over time, highlighting regional strengths and identifying growth opportunities.

----

## Data Source
The dataset was imported into Excel and transformed in Power Query. 

Sample of the PDF data:

![Screenshot](/images/Screenshot%20093753.png)

----

## Preparation Tools
  - Power Query: Power Query in Excel was used to extract, clean, shape the data. Also, it was used to develop a pipeline that cut manual processing from 4 hours to 20 minutes
    
  - Power Pivot: This enabled the writing of the DAX (Data Analysis Expressions).
    
  The key measures created includes:
  - Total Sales = SUM(Sales[Amount])
  - Total Profit = SUM(Sales[Profit])
  - YoY Growth = DIVIDE([Total Sales] - [Last Year Sales], [Last Year Sales])
  - Profit Margin = DIVIDE([Profit], [Sales])
    
    ![Screenshot](/images/Screenshot%20093832.png)

    ![Screenshot](/images/Screenshot%20093846.png)


----

## Data Processing
----
Data Transformation in Power Query: The following process was taken to prepare data for analysis:
  - Removing data duplicates
  - Removing errors
  - Standardization of data
  - Removing null values and blank

----

## Skills Demonstrated
   - Data Transformation: Transforming the data in Power Query.
   - Data Processing and Cleaning: Correcting errors and inconsistencies in data using Power Query.
   - Data Analysis: Gaining comprehensive insights using DAX measures.
   - Visualization and Reporting: Presenting findings with clear insights using the right visuals that solves specific problems.
   - Critical Thinking and Problem-Solving: Identifying trends, uncertainties and disparities in different regions.

----

## Objective
The key objective of the analysis includes:
   - Compare Sales, Profit, Cost, and Quantity between 2023 and 2024.
   - Analyze monthly revenue trends to track growth patterns and performance consistency.
   - Evaluate regional sales distribution across North, South, East, and West regions.
   - Examine product-wise sales breakdown to identify top-performing items.
   - Provide actionable insights for strategic business decisions.
     
----

## Insights

----

Sales Overview:

----

![Screenshot](/images/Screenshot%20101034.png)

The KPI cards shows the following:

- Total Sales (2024): $476K → 🔼 30% increase vs LY (2023)
- Total Quantity Sold: 899 units → 🔼 24% increase vs LY
- Total Cost: $64K → 🔼 11% vs LY
- Total Profit: $412K → 🔼 34% vs LY

Key Takeaway: This indicates strong growth in both revenue and profitability, showing efficient cost control and improved sales performance year-over-year.

----

Monthly Revenue Trend (2023 vs 2024)

----

![Screenshot](/images/Screenshot%20100950.png)

The line graph shows the following:
- A visible upward trend in 2024 revenue across most months.
- Seasonal dips noted around May and December suggesting potential demand fluctuations.
- Steady growth from June to October, implying effective mid-year sales strategies.

----

Regional Sales Distribution

----

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
