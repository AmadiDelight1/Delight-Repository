# EMPLOYEE ATTRITION ANALYSIS
----
# Table of Contents
----
- [Analysis Overview](#analysis-overview)
- [Data Source](#data-source)
- [Preparation Tools](#preparation-tools)
- [Data Processing](#data-processing)
- [Skills Demonstrated](#skills-demonstrated)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)

----

## Analysis Overview

----

Employee attrition remains one of the biggest challenges for organizations.The HR Attrition Analytics dashboard provides a comprehensive analysis of employee behavior, satisfaction and demographics.The dashboard helps HR teams uncover root causes of attrition and make evidence based decisions that support retention and workforce planning.

Key questions answered include:
- What factors contribute most to attrition?
- Are certain age groups or departments more vulnerable?
- How do job satisfaction and work-life balance influence resignations?
- What insights can HR leaders use to improve retention strategies?
  
----

## Data Source

----

Built a data pipeline from Kaggle to Excel using Python and Kaggle API generated from Kaggle and transformed in Power Query.

Sample of the Python script and dataset:

![Screenshot](/images/Screenshot%20162658.png)

![Screenshot](/images/Screenshot%20162758.png)

![Screenshot](/images/Screenshot%20163920.png)

----

## Preparation Tools

----

  - Python: Kaggle environment was created on Anaconda and the dataset was downloaded using pythin script, Also the Kaggle API was authenticated on this platform. The process cut manual processing from 6 hours to 10 mins.
  - Excel Power Query: The dataset was transformed and cleaned using this tool. A process that makes automation easy for subsequent refreshing.
  - Excel Power Pivot: Perform exploratory analysis, create dax measures and pivot table.

![Screenshot](/images/Screenshot%20183433.png)

Creating key measures with DAX: The key measures created includes:
        - Total Employee: Counts the total number of employees in the dataset. This is the baseline number for calculating other metrics.
        - Attrition Count: Counts how many employees left the company. This measure filters the table to capture only rows where Attrition = “Yes”.
        - Attrition Rate: This measure calculates the percentage of employees who left.
        - Avg Income: This measure pulls the overall average monthly income across all employees.

 ![Screenshot](/images/Screenshot%20181150.png) 

----

## Skills Demonstrated

----

   - Automated Dataset Retrieval Using Python & Kaggle API
   - Data Cleaning & Preparation in Python
   - Pivot Table & Dashboard Development
   - Automation between Python and Excel
   - Analytical Storytelling
   - Critical Thinking
   - Proble Solivng
     
----

## Insights

----

Does Work-Life Balance Rate affect Attrirtion Rate?

![Screenshot](/images/Screenshot%20164310.png)

The chart shows Attrition rates by work-life balance rating:
- Poor → 31.3%
- Fair → 16.9%
- Good → 14.2%
- Great → 17.6%

Key Takeaway:
Employees with Poor worklife balance are twice as likely to leave which shows that workload imbalance is a major risk.

----

How deos Job Satisfaction Rate affect Attrition?:

![Screenshot](/images/Screenshot%20093824.png)

This visual shows comparison of attrition between “Yes” (left) and “No” (stayed) groups across satisfaction levels.

Key Takeaways:
Even employees reporting Good and Great satisfaction exhibit significant attrition, signaling issues beyond satisfaction.

----

How many employee left each Department?

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
