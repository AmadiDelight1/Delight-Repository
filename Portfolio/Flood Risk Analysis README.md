# LAGOS FLOOD RISK ANALYSIS (2010-2024)
----
# Table of Contents
----
- [Problem Statement](#problem-statement)
- [Analysis Overview](#analysis-overview)
- [Data Source](#data-source)
- [Preparation Tools](#preparation-tools)
- [Data Processing](#data-processing)
- [Skills Demonstrated](#skills-demonstrated)
- [Objective](#objective)
- [Insights & Recommendations](#insights-&-recommendations)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)
- [Dashboard Interaction]([https://app.powerbi.com/groups/me/reports/3fe4b636-75a1-4f7b-907b-4cf622bc0047/5a2f51367c78662f0178?experience=power-bi])
  
----

## Problem Statement

----

Lagos, one of Africa’s fastest-growing coastal cities, faces increasing flood risks driven by climate change, rapid urbanization, poor drainage infrastructure, and changing weather patterns. Each year, intense rainfall and rising sea levels lead to widespread flooding, damaging homes, roads, and public utilities and in many cases costing lives.

Despite the scale of the problem, flood management strategies in many urban centers remain largely reactive rather than proactive. Limited access to actionable weather insights makes it difficult for policymakers, urban planners, and disaster response agencies to anticipate high-risk periods or implement timely interventions. As a result, the city continues to experience recurring human, social, and economic losses that could be mitigated with better data-driven decision-making.

----

## Analysis Overview

----

This project was designed to investigate flood trends, identify key weather variables, uncover seasonal risk patterns, and generate actionable insights that can guide short-term mitigation and long-term adaptation strategies. By analysing over a decade of weather data (2010–2024), the project leverages data analytics and visualization to translate complex meteorological information into practical intelligence for decision-makers, city planners, emergency responders, and environmental stakeholders with the ultimate goal of saving lives, reducing vulnerability, and strengthening urban resilience.

----

## Data Source

----
The dataset was collected from Nigerian Meteorological Agency (NiMet) website, transformed in google sheet and extracted to Power BI through web option.

----

## Preparation Tools

----
  - Google Sheet: This was used to extract, clean and transform the dataset. Also, it was used to develop a pipeline that cut manual processing from 4 hours to 20 minutes
  - Power BI: This was used to create visuals that solve specific problems and real time insights that drives accurate decision making.
    
----

## Data Processing

----

Data Transformation in Google Sheet: The following process was taken to prepare data for analysis:
  - Removing data duplicates
  - Removing errors
  - Standardization of data
  - Removing null values and blanks
  - Creating month, year, seasons from the date column. Then, rainfall intensity and flood flag risk from the precipitation and sea level pressure column.
  - Identifying and removing anomalies.
    
 Sample of the Transformed data:

 ![Screenshot](/images/Screenshot%20151445.png)

Data Modelling: A star schema relationship was created for the fact table and calendar table, and the data was stored as import to enhance performance during automation.

![Screenshot](/images/Screenshot%20062140.png)

Dax Measures:
The key measures created includes:
- Total Rainfall (mm): Total precipitation from 2010-2024
- Average Sea Level Pressure: Mean sea-level pressure
- Flood Risk Events: Count of days meeting flood risk condition	
- Average Rainfall on Flood Days: Average rainfall days > 50 mm precipitation

![Screenshot](/images/Screenshot%20062929.png)

----

## Skills Demonstrated

----
   - Data Transformation and Extraction: Transforming data in google sheet and extracting to Power Bi through web option. 
   - Data Processing and Cleaning: Correcting errors and inconsistencies in data using Google sheet.
   - Data Analysis: Gaining comprehensive insights using DAX measures.
   - Visualization and Reporting: Presenting findings with clear insights using the right visuals that solves specific problems.
   - Critical Thinking and Problem-Solving: Identifying trends, key weather variables that causes flood and uncovering seasonal risk patterns.

----

## Objective

----

The key objective of the analysis includes:
   - Investigate historical flood trends over a 14-year period.
   - Identify critical weather variables such as rainfall intensity, precipitation probability, and sea-level pressure that contribute to flood risk.
   - Uncover seasonal risk patterns to pinpoint high-risk periods for targeted interventions.
   - Generate actionable insights to support short-term flood mitigation planning and long-term climate adaptation strategies.
     
----

## Insights & Recommendations

----

Which season influence flood risk events?:

![Screenshot](/images/Screenshot%20062623.png)

This donut chart compares the rainy season against the dry season for the time range indicated.The rainy season (Apr–Oct) accounts for 72% of all flood risk events

Recommendation:
Most flood risks occur in the rainy season, particularly August–October. Therefore, early drainage maintenance and awareness campaigns should target this window.

----

Are flood risk events becoming frequent over time?

![Screenshot](/images/Screenshot%20062535.png)

This line chart tracks flood risk event from 2010 to 2020. The result shows that flood risk events increased by 45% between 2010 and 2024, with peaks in 2016 and 2022.

Recommendation:
Flood risk is increasing over time so this highlights the need for adaptive city planning and resilient infrastructure.

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

## Dashboard

----

![Screenshot](/images/Screenshot%20071857.png)

----

## Conclusion

----

Between 2010 to 2024, 72% of flood risk events occurred during the rainy season, with an average rainfall of 63 mm on those days. Over 31% of those events were linked to high-intensity rainfall combined with sea-level pressure below 1010 hPa, highlighting the urgent need for enhanced drainage capacity and early warning systems before May each year.
