# EMPLOYEE ATTRITION ANALYSIS
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
Many organizations struggle to understand why employees leave, who is most at risk, and which factors contribute the most to workforce attrition. Without clear insights, HR departments face challenges such as Rising turnover rate, Hiigh recruitment cost, Loss of skilled talent and Declining employee morale.
HR teams often collect large amounts of employee data but lack the analytical skills to convert it into actionable insights.

This dashboard solves that problem by transforming HR data into a simple, interactive and insights-driven tool that helps organizations make smarter decisions about retention, engagement and workforce planning.

----

## Data Source
Built a datapipeline from Kaggle to Excel using Python and Kaggle API generated from the Kaggle and transformed in Power Query.

Sample of the PDF data:

![Screenshot](/images/Screenshot%20163920.png)

----

## Preparation Tools
  - Python: Kaggle environment was created on Anaconda and the dataset was downloaded using pythin script, Also the Kaggle API was authenticated on this platform. The process cut manual processing from 6 hours to 10 mins.
  - Power Query: The dataset was transformed and cleaned using this tool. A process that makes automation easy for subsequent refreshing.
    
----

Data Modelling: A star schema relationship was created for the fact table and calendar table, and the data was permanently stored as import to enhance performance during automation.

   - Creating key measures with DAX: The key measures created includes:
        - Average LBW Estimate Cases: This measure computes the mean percentage of low birth weight across all regions.
        - Uncertainty Range: This KPI helps stakeholders identify regions where data quality is strong versus where further investigation is needed.
        - Lower Credible Interval: It allows users to evaluate the confidence range of the dataset.
        - Upper Credible Interval: It helps users understand the potential upper limit of uncertainty in the data.
     
        ![Screenshot](/images/Screenshot%20175821.png)

----

## Skills Demonstrated
   - Data Transformation and Extraction: Extracting PDF data and transforming the data in Power Query.
   - Data Processing and Cleaning: Correcting errors and inconsistencies in data using Power Query.
   - Data Analysis: Gaining comprehensive insights using DAX measures.
   - Visualization and Reporting: Presenting findings with clear insights using the right visuals that solves specific problems.
   - Critical Thinking and Problem-Solving: Identifying trends, uncertainties and disparities in different regions.

----

## Objective
The key objective of the analysis includes:
   - Average LBW cases regionally
   - Statistical confidence intervals
   - Regional variability and uncertainty
   - Long-term prevalence trends
   - Key regions with the highest burden
     
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
