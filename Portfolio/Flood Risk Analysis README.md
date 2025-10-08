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
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)
- [Dashboard Interaction](https://app.powerbi.com/groups/me/reports/3fe4b636-75a1-4f7b-907b-4cf622bc0047/5a2f51367c78662f0178?experience=power-bi)
----

## Problem Statement
Lagos, one of Africa’s fastest-growing coastal cities, faces increasing flood risks driven by climate change, rapid urbanization, poor drainage infrastructure, and changing weather patterns. Each year, intense rainfall and rising sea levels lead to widespread flooding, damaging homes, roads, and public utilities and in many cases costing lives.

Despite the scale of the problem, flood management strategies in many urban centers remain largely reactive rather than proactive. Limited access to actionable weather insights makes it difficult for policymakers, urban planners, and disaster response agencies to anticipate high-risk periods or implement timely interventions. As a result, the city continues to experience recurring human, social, and economic losses that could be mitigated with better data-driven decision-making.

----

## Analysis Overview
This project was designed to investigate flood trends, identify key weather variables, uncover seasonal risk patterns, and generate actionable insights that can guide short-term mitigation and long-term adaptation strategies. By analysing over a decade of weather data (2010–2024), the project leverages data analytics and visualization to translate complex meteorological information into practical intelligence for decision-makers, city planners, emergency responders, and environmental stakeholders with the ultimate goal of saving lives, reducing vulnerability, and strengthening urban resilience.

----

## Data Source
The dataset was collected from Nigerian Meteorological Agency (NiMet) website, transformed in google sheet and extracted to Power BI through web option.

----

## Preparation Tools
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
   - Data Transformation and Extraction: Transforming data in google sheet and extracting to Power Bi through web option. 
   - Data Processing and Cleaning: Correcting errors and inconsistencies in data using Google sheet.
   - Data Analysis: Gaining comprehensive insights using DAX measures.
   - Visualization and Reporting: Presenting findings with clear insights using the right visuals that solves specific problems.
   - Critical Thinking and Problem-Solving: Identifying trends, key weather variables that causes flood and uncovering seasonal risk patterns.

----

## Objective
The key objective of the analysis includes:
   - Investigate historical flood trends over a 14-year period.
   - Identify critical weather variables such as rainfall intensity, precipitation probability, and sea-level pressure that contribute to flood risk.
   - Uncover seasonal risk patterns to pinpoint high-risk periods for targeted interventions.
   - Generate actionable insights to support short-term flood mitigation planning and long-term climate adaptation strategies.
     
----

## Insights

----

Which regions have wider uncertainty ranges?:

![Screenshot](/images/Screenshot%20092332.png)

This scatter plot compares the LBW estimate (%) against the uncertainty range for each region. Regions such as West-Central Africa (W-C Africa) and South Asia shows higher uncertainty and higher LBW prevalence. High-income regions and Central & Eastern Europe (CEE) display lower uncertainty, indicating more reliable data and narrower variability.

Key Takeaway:
Data uncertainty is highest in regions with weaker health surveillance systems, often low-income and high-burden areas.
Investment in better data collection could significantly improve the accuracy of LBW estimates in these regions.

How has LBW prevalence changed over time across the top 5 regions?:

![Screenshot](/images/Screenshot%20092347.png)

This line chart tracks LBW prevalence from 2000 to 2020. Although all regions show a slight downward trend, South Asia and West-Central Africa remain the highest contributors. Latin America and the Caribbean (LAC) and Middle East & North Africa (MENA) exhibit gradual declines.

Key Takeaways:
- Progress is uneven: Despite global improvement, some regions are still above 20% LBW prevalence.
- Persistent hotspots: South Asia and Sub-Saharan Africa continue to bear the heaviest burden, suggesting targeted interventions are needed.

Which regions have the highest LBW cases?:

![Screenshot](/images/Screenshot%20092401.png)

Region Prevalence
South Asia	21%
East-Southern Africa	17%
West-Central Africa	15%
Middle East & North Africa (MENA)	15%
Latin America & Caribbean (LAC)	11%
Central-Eastern Europe (CEE)	11%
High-Income Countries	9%
East Asia-Pacific	9%

Key Takeaway:
- South Asia stands out with the highest LBW prevalence (21%), far exceeding the regional average.
- African regions follow closely, emphasizing the need for maternal health and nutrition interventions.
- High-income countries and East Asia-Pacific report the lowest rates (<10%), likely due to better prenatal care and socioeconomic conditions.

----

## Recommendations

----

Policy & Intervention Priorities: 
- South Asia and Sub-Saharan Africa require focused policies addressing maternal nutrition, antenatal care, and healthcare access.
- Data quality improvements in high-uncertainty regions can enable better resource allocation and targeted programs.
-Long-term strategies should consider both prevalence trends and uncertainty levels to design more resilient maternal health systems.

For Monitoring & Evaluation:
- Use uncertainty metrics as indicators of data quality and system reliability.
- Track temporal changes to measure policy effectiveness and detect emerging risks.

----

## Dashboard

![Screenshot](/images/Screenshot%20071857.png)

----

## Conclusion
The Low Birth Weight Insights Dashboard provides a powerful lens into regional LBW landscape. While overall prevalence has slightly declined over the last two decades, significant disparities remain. Regions like South Asia and West-Central Africa face persistent challenges, compounded by high uncertainty and weaker health systems.

Achieving substantial reductions in LBW will require:
- Strengthening maternal and child health programs
- Improving data collection infrastructure
- Targeted resource deployment in the most affected regions.
