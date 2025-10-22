# RETAIL SALES PERFORMANCE ANALYSIS USING SQL
----
# Table of Contents
----

- [Problem Statement](#problem-statement)
- [Analysis Overview](#analysis-overview)
- [Data Source](#data-source)
- [Data Processing](#data-processing)
- [Skills Demonstrated](#skills-demonstrated)
- [Recommendation](#recommendation)
- [Conclusion](#conclusion)

----

## Problem Statement

----

In today’s competitive retail environment, businesses generate large volumes of transactional data daily, yet many struggle to extract meaningful insights that can guide strategic decisions.
Many companies lacks visibility into key sales performance metrics such as top-performing product categories, customer purchasing behavior and seasonal sales trends.

Without this insight, management faces challenges in:
- Identifying which products or categories drive the highest revenue.
- Understanding customer demographics, spending patterns and preference
- Recognizing the months or seasons that yield peak or low sales performance.
  
To address this challenge, SQL-based data analysis is used to uncover hidden patterns, evaluate sales performance, and generate actionable insights that can improve decision-making, profitability, and customer engagement.

----

## Analysis Overview

----

This project focuses on:
- Identifying top-performing product categories based on total sales.
- Understanding customer demographics, preferences and engagement.
- Identify time based trends to understand seasonality and revenue forecasting.
  
The project aims to answer critical business questions that guide marketing strategy, product optimization, and customer segmentation. By leveraging SQL for data aggregation and analysis, this project provides clear, data-driven insights to support retail business decisions.

----

## Data Source

----
The dataset was imported as csv to SQL into a retail database created, cleaned and transformed in SQL.

----

## Data Processing

----

Data Transformation in SQL: The following processes was carried out to prepare data for exploratory analysis:
  - Removing data duplicates

  ![Screenshot](/images/Screenshot%20110706.png)

  - Standardization of data

  ![Screenshot](/images/Screenshot%20111453.png)

  - Removing null values

  ![Screenshot](/images/Screenshot%20121810.png)

----

## Skills Demonstrated

----
   - Data Transformation and Extraction: Transforming data in SQL
   - Data Processing and Cleaning: Correcting errors and inconsistencies in data using SQL
   - Data Analysis: Gaining comprehensive insights by handling exploratory analysis on the dataset. 
   - Critical Thinking and Problem-Solving: Solving business problems by using the right functions to query data.

----

## Insights

----

Which product categories generate the highest total sales?

![Screenshot](/images/Screenshot%20123013.png)

Electronics leads in total sales, followed by Clothing. Beauty products lags behind, suggesting potential for targeted marketing or product repositioning.

Business Implications:
Prioritize inventory and marketing for high-performing categories. Investigate pricing or promotion strategies to boost the selling of Beauty products.

----

Who are the main customers purchasing Beauty products, and what is their average age?

![Screenshot](/images/Screenshot%20123048.png)

The Beauty category attracts adults aged 50–58 years on average. This indicates a mature, possibly professional demographic with consistent purchasing power.

Business Implications:
Develop marketing campaigns tailored to this older audience and also consider loyalty rewards or premium products aligned with their preferences.

----

What is the average sales amount for each month, and which month records the highest sales in each year?

![Screenshot](/images/Screenshot%20123217.png)

The results show how average sales fluctuate across months within each year.

![Screenshot](/images/Screenshot%20173959.png)

December consistently shows the highest sales month, likely due to holiday shopping and year-end bonuses. Also, Feb and March tend to record lower sales, possibly due to post holiday spending fatigue. This confirms that sales performance is seasonal, with specific peak periods driving the company’s revenue.

Business Implications: 
- Plan marketing campaigns, inventory levels and staffing effectively should be prioritized. Seasonal spikes indicate that sales strategies should be intensified before and during this best selling month.
- Introduce discounts, loyalty offers or new launches to stabilize revenue flow during Feb and March.

----

Which customers contribute the most to overall revenue, and who are the top 5 based on their total purchase value?

![Screenshot](/images/Screenshot%20123333.png)

The query identifies the top 5 highest-spending customers, showing who contributes the largest share of total revenue. These customers may represent a small percentage of the base but account for a significant portion of total sales

Business Implications:
- The business is reliant on this few number of people meaning customer retention is critical.
- Losing any of these top spenders could cause a notable drop in revenue.
- These customers preferences can influence product focus and marketing strategies.

----

## Recommendation:

----

- Launch targeted ads for Beauty products focusing on adult audiences.
- Maintain high stock for Electronics and Clothing due to strong performance.
- Run seasonal promotions for underperforming categories.
- Monitor category sales trends quarterly to identify shifts in consumer demand.
- Launch campaigns one month before high-performing months (for instance, promote sales in November to capture December demand).
- Increase stock and logistics readiness for peak months to avoid shortages.
- Introduce limited-time discounts or bundle offers during low-sales months to encourage spending.
- Offer loyalty rewards or exclusive deals to retain top customers.
- Promote complementary products to increase average transaction value.
- Identify traits of top customers and target similar profiles through marketing campaigns.
  
----

## Conclusion

----

This project demonstrates how SQL analytics can uncover valuable retail insights from raw data. By understanding sales distribution and customer demographics, businesses can:

- Drive data-informed decisions
- Strengthen marketing campaigns
- Improve customer engagement and sales performance
  
----

PS: If you find this project valuable, don’t forget to star the repository.

