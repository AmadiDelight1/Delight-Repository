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

### KPI Overview:

----

![Screenshot](/images/Screenshot%20201001.png)

The KPI cards shows the following:
- Total Revenue this week: $97K (+13.8% vs. last week)
- Total Profit this week: $26K (+10.7% vs. last week)
- Total Orders: 42
- Total Customers: 42

Revenue for this week ($96,541) represents 1.88% of the total revenue ($5,148,133).

----

### Revenue Trend

----

![Screenshot](/images/Screenshot%20200859.png)

The line graph shows that:

Dec 24 recorded a sharp revenue spike nearly double the weekly daily average of $13,792. This is likely driven by last-minute pre-Christmas purchases. Revenue then dropped significantly across Dec 25–27, consistent with post-Christmas shopping lulls and potential store or fulfilment closures. A recovery trend is clearly visible from Dec 28 through Dec 30, with revenue climbing steadily back toward and above the weekly average by the final day of the period. This V-shaped dip-and-recovery pattern is characteristic of holiday retail cycles and suggests underlying demand remains healthy heading into the new week.

----
### Pareto-based Performance Analysis
----

Sales Performance by Category

----

![Screenshot](/images/Screenshot%20202004.png)

|    Category          |              Revenue               |             Pareto Position          | 
|----------------------|------------------------------------|--------------------------------------|  
|     Furniture        |            ~$36K                   |          #1 — 38% cumulative         | 
|     Electronics      |            ~$20K                   |          #2 — 58% cumulative         |            
|     Home Appliances  |            ~$19K                   |          #3 — 78% cumulative         | 
|     Toys             |            ~$11K                   |          #4 — 89% cumulative         | 
|     Fashion          |            ~$10K                   |          #5 — 100%                   | 

Furniture alone drives 38% of weekly revenue, making it the single most critical category. Furniture and Electronics together account for 58% meaning just 2 of 5 categories generate the majority of sales.

----

Sales Performance by Sub-category

----

![Screenshot](/images/Screenshot%20201944.png)

Queen Bed Frame is the highest-revenue product, generating ~$26K (~28% cumulative), far outpacing all other SKUs.
The top 4 products (Queen Bed Frame, Sony Headphones, Dining Table, Polo Shirt) collectively account for approximately 58% of product revenue.
The long tail of products (Lego Set, Dell XPS 15, Puzzle Box, Sneakers V2, Maxi Dress and Office Chair) are well into the Pareto threshold zone, contributing little to total revenue.

----

Sales Performance by Sales Person

----

![Screenshot](/images/Screenshot%20201802.png)

|    Sales Person      |              Revenue               |             Pareto %                 | 
|----------------------|------------------------------------|--------------------------------------|  
|     Emily Garcia     |            ~$31K                   |              32%                     | 
|     Angela Kim       |            ~$24K                   |              58%                     |            
|     James Brown      |            ~$20K                   |              79%                     | 
|     Sarah Johnson    |            ~$10K                   |              90%                     | 
|     Mike Lee         |            ~$10K                   |              100%                     | 

Emily Garcia is the top revenue generator, responsible for 32% of weekly sales revenue on her own. The top 3 salespeople (Emily, Angela, James) collectively drive 79% of total weekly sales revenue distribution. Sarah Johnson and Mike Lee represent an opportunity for coaching and performance uplift.

----

Sales Performance by Customer

----

![Screenshot](/images/Screenshot%20201833.png)

- Jason Mack is the highest-value customer this week at ~$7K, followed by Robert Peterson and Mrs. Amy Watson.
- The top 8 customers account for approximately 60% of total weekly customer revenue.
- A long tail of 30+ customers in the threshold zone each contribute very small individual amounts, suggesting opportunities for upselling and re-engagement programmes.

----

Sales Performance by Region

----

![Screenshot](/images/Screenshot%20201742.png)

|    Region            |              Revenue               |             Pareto %                 | 
|----------------------|------------------------------------|--------------------------------------|  
|     Central          |            ~$43K                   |              44%  cumulative         | 
|     West             |            ~$22K                   |              66%  cumulative         |            
|     South            |            ~$19K                   |              85%  cumulative         | 
|     East             |            ~$14K                   |              100% cumulative         | 

The Central region dominates, contributing 44% of weekly revenue alone. Central and West together account for 66%, crossing the Pareto significance threshold. The East region is the lowest performer and should be prioritised for targeted regional strategies.

----

Sales Performance by State

----

![Screenshot](/images/Screenshot%20183807.png)

Illinois is the #1 state, contributing 18% of weekly revenue by itself. The top 7 states (Illinois through Texas) collectively account for 79% of state-level revenue — the Pareto threshold. States like Georgia, Massachusetts, and New Jersey are significantly underperforming and require dedicated strategies.

----

Order Status Breakdown

----
![Screenshot](/images/Screenshot%20200912.png)

Only 36% of this week's orders have been fully delivered. Over 38% of orders are still unconfirmed or newly placed, indicating pipeline management opportunities to accelerate order processing and fulfilment velocity.

----
## Recommendations

----

Based on the Pareto analysis across all dimensions, the following strategic recommendations are proposed:

Double Down on Top Performers: 
- Furniture and Electronics should receive priority in inventory management, promotions and marketing spend.
- Queen Bed Frame and Sony Headphones are star SKUs, ensure stock availability and consider bundling strategies to increase average order value.
- Emily Garcia and Angela Kim are top-performing sales reps, document their sales approaches and use it as internal benchmarks for team training.

Develop Underperforming Segments
- East region and states like Georgia, Massachusetts and New Jersey fall well outside the Pareto performance zone. Deploy region-specific campaigns, local partnerships or targeted digital advertising.
- Mike Lee and Sarah Johnson need structured coaching plans, performance targets and potentially account reassignments to better leverage high-potential territories.

Invest in High-Value Customer Retention
- The top 8 customers driving ~60% of customer revenue warrant VIP treatment such as personalised outreach, loyalty rewards and early access to new products.
- Re-engagement campaigns should target the long-tail customer base with relevant product offers based on purchase history.

Accelerate Order Fulfilment
- With 38% of orders still in early pipeline stages, focus on reducing confirmation-to-shipment cycle times.
- Consider automated order confirmation workflows and proactive customer communication to improve fulfilment velocity and customer satisfaction scores.

Grow the Central and West Regions
- The Central region is the clear revenue engine,  protect and grow this market through deeper local sales investment and exclusive product availability.
- West region shows strong cumulative contribution (66%) and has room to grow toward Central-level performance with additional sales rep support.

Review Long-Tail Product Portfolio
- Products falling in the 80–100% Pareto cumulative zone (Lego Set, Dell XPS 15, Office Chair, Maxi Dress, etc.) should be evaluated for discontinuation, bundling or discounting to optimise working capital and shelf space.
  
----

## Dashboard

![Screenshot](/images/Screenshot%20184442.png)
![Screenshot](/images/Screenshot%20183807.png)

- Blue bars: Revenue per segment (descending order)
- Green line: Cumulative Pareto percentage
- Red/threshold line: 80% Pareto cutoff indicator
- Purple shading: Segments falling beyond the threshold (long tail)

----

## Conclusion

---
This Retail Sales Performance Analysis confirms that revenue is highly concentrated across Delight's Store operations, a classic manifestation of the Pareto Principle. A small number of categories, products, sales representatives, customers, and geographic regions are responsible for the overwhelming majority of weekly revenue.
This week's performance is encouraging: total revenue grew +13.8% and total profit grew +10.7% versus the prior week, led by strong results in Furniture, the Central region, Illinois, and top performers like Emily Garcia and Jason Mack.

However, the analysis also reveals meaningful opportunities: underperforming states in the East, a long tail of low-revenue products straining inventory, a fulfilment pipeline where nearly 40% of orders are unconfirmed or new, and sales representatives who would benefit from structured development.

By acting on the Pareto-driven insights surfaced in this dashboard, Delight's Store leadership can make smarter, faster, and more targeted decisions by concentrating resources where they generate the greatest return while designing recovery strategies that lift the bottom of the performance curve.

Connect with me!

📂 Portfolio by: Delight Amadi
🔗 Repository: Delight-Repository on GitHub
📅 Analysis Period: This Week
📧 Email: Nobledelight7@gmail.com

