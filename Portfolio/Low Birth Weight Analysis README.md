# LOW BIRTH WEIGHT ANALYSIS
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
- [Dashboard Interaction](https://app.powerbi.com/groups/me/reports/c85de3ac-4038-4785-9237-0b0b6cc18185/fd61d198c31c2463f7b9?experience=power-bi)
----

## Analysis Overview
Low birth weight is defined as a birthweight of less than 2,500 grams. it is a critical global health challenge that significantly contributes to infant morbidity, mortality and long-term developmental complications. This analysis aims to identify disparities, highlight progress, expose trends in prevalence and case counts over time and pinpoint areas lagging in LBW reduction. Drawing imsights from this analysis will guide interventions to improve maternal and child health and will accelerate progress towards reducing the global burden of low birth weight.

----

## Data Source
The dataset was collected from UNICEF/WHO LBW estimate cases and extracted to Power BI in PDF format, then transformed in Power Query.

Sample of the PDF data:

![Screenshot](/images/Screenshot%20180743.png)

----

## Preparation Tools
  - Power Query: This was used to extract, clean, shape, pivot and unpivot data. Also, it was used to develop a pipeline that cut manual processing from 4 hours to 20 minutes
  - Power BI: This was to create visuals that solve specific problems and real time insights that drives accurate decison making.
    
----

## Data Processing
----
Data Transformation in Power Query: The following process was taken to prepare data for analysis:
  - Removing data duplicates
  - Removing errors
  - Standardization of data
  - Removing null values and blanks
  - Append tables
    
    ![Screenshot](/images/Screenshot%20175855.png)

Data Modelling: A star schema relationship was created for the fact table and calendar table, and the data was permanently stored as import to enhance performance during automation.

![Screenshot](/images/Screenshot%20175938.png)

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

   - Positive Cash Flow: The Net Cash Flow of ₦224,850 indicates that deposit still exceeds the withdrawal even though there was a high spend resulting in net gain.

   - Cumulative Frequency by Month: The pattern suggest that the finance is drained over time. Understanding this pattern could be useful for keeping in check overspending habits.

   - Imbalance in Inflow and Outflow: Though this did not result in a negative cash flow, It affects the net cash flow compared to the total inflow. Indicating that the net cash flow might be affected if the frequency of expenses continue to increase.

   - Top Spending Withdrawals: While rent is a fixed expense, controlling one-off appliances spending could increase overall cash flow rate from 20%.

----

## Recommendations

----

   - There is a good cash inflow but the problem is high withdrawal. Limit withdrawals to basic needs like rent and groceries amd utilities. This might be hard, but developing a disciplined approach to withdrawal can improve growth rate.

----

## Dashboard

----

![Screenshot](/Project/Screenshot1%20014850.png)

Using trigger and action features in Power BI and Zapier the dashboard will be automated on 7th of every month to enhance performance and aid accurate reading.


     
