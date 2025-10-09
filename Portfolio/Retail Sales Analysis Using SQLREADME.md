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

Which weather variable highly influence flood?

![Screenshot](/images/Screenshot%20062546.png)

The stacked column chart shows that high rainfall intensity is the dominant trigger, often coupled with low sea-level pressure which is < 1010 (hPa)

Recommendation:
Low sea level is one of the variable that influence flood risk. Threfore,  continuous atmospheric pressure tracking can serve as an early flood warning signal. 

----

What percentage of high-intensity rainfall days result in flood risk?

![Screenshot](/images/Screenshot%20062636.png)

The guage chart shows that approximately 31% of high-intensity rainfall days result in flood conditions.

Recommendation:
Urban drainage systems should be designed to handle rainfall intensities above 50 mm/day which is identified as high rainfall intensity.

----

## Conclusion

----

Between 2010 to 2024, 72% of flood risk events occurred during the rainy season, with an average rainfall of 63 mm on those days. Over 31% of those events were linked to high-intensity rainfall combined with sea-level pressure below 1010 hPa, highlighting the urgent need for enhanced drainage capacity and early warning systems before May each year.

----

PS: If you find this project valuable, don’t forget to star the repository.

