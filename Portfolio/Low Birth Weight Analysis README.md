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
- [Data Analysis and Visualization](#data-analysis-and-visualization)
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
    
    ![Screenshot](/Project/Screenshot%20175855.png)

Data Modelling: A star schema relationship was created for the fact table and calendar table, and the data was permanently stored as import to enhance performance during automation.

![Screenshot](/Project/screenshot%20044827.png)

Data Preparation in Power BI: To further prepare the data for analysis I created the following:
   - Creating of Calender Table: This was created to facitate time-based analysis. First, the date column was created followed by the extraction of Year, Month, MonthNo and Quarter using the Date and Format function.
     
     ![Screenshot](/Project/Screenshot%20175938.png) 

   - Creating key measures with DAX: The key measures created includes:
        ○ Total Income: This is sum of all cash inflow.
        ○ Total Expenses: This is the sum of all cash outflow.
        ○ Total Balance: This is the net cash flow for inflow and outflow.
        ○ Growth rate: This is the use to determine month over month increase or decrease betwwen inflow and outflow.
     
        ![Screenshot](/Project/Screenshot%20013439.png)

----

## Skills Demonstrated
   - Data Transformation and Extraction: Extracting PDF data from gmail and transforming the data in Power BI.
   - Data Processing and Cleaning: Correcting errors and inconsistencies in data using Power Query.
   - Data Analysis: Gaining comprehensive insights using DAX measures.
   - Visualization and Reporting: Presenting findings with clear insights using the right visuals.
   - Critical Thinking and Problem-Solving: Identifying trends and implementing proposed change for financial growth.

----

## Objective
The key objective of the analysis includes:
   - Track cash inflow and outflow from Jan 2025 to Sept 2025.
   - Compare the inflow and outflow growth rate.
   - Determine the cumulative net cash flow to have a comprehensive financial overview.
   - Identify the categories with the highest spending.

----

## Data Analysis and Visualization
----
Monthly Income and Expenses:

![Screenshot](/Project/Screenshot%20013229.png)

The highest monthly inflow was recorded in February with a total of ₦552,713.62 and lowest inflow was recorded in September with a total of ₦700. Also, the same month has the highest outflow with a total of ₦470,210.78 and lowest outflow was recorded in June with a total of ₦54. This suggests that February was an active month for deposit and withdrawal.

Top Spending Category:

![Screenshot](/Project/Screenshot%20013305.png)

The largest withdrawal occurred on Feb 12, 2025, with transaction amount totaling ₦331,064.07 and the secong highest withdrawal occurred on Jan 20, 2025 with transaction amount totaling ₦98,000. These transactions significantly increased the overall outflow.

Cash Flow Rate:

![Screenshot](/Project/Screenshot%20013330.png)

The rate for cash flow is 20% when compared to total cash inflow. This means that after expenses a total of ₦224,850 remained from ₦1,150,000.

Monthly Growth Rate:

![Screenshot](/Project/Screenshot%20013210.png)

July witnessed a sudden massive inflow growth rate of 4031% which was followed by a high spend rate of 34948%. This was clearly shown in the picture above. This shows there was no sustainable growth.

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


     
