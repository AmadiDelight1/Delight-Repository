# PERSONAL FINANCE ANALYSIS
----
# Table of Contents
----
- [Financial Overview](#financial-overview)
- [Data Source](#data-source)
- [Preparation Tools](#preparation-tools)
- [Data Processing](#data-processing)
- [Skills Demonstrated](#skills-demonstrated)
- [Objective](#objective)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Dashboard](#dashboard)
- [Dashboard Interaction](https://app.powerbi.com/groups/me/list?experience=power-bi)

----

## Financial Overview
This report presents a comprehensive overview analysis of my sister personal bank statement from Jan 2025 to Sept 2025, based on the provided dataset. The primary objective of this analysis is to automate workflow for her bank statament in other to monitor her personal finance cash flow over a period of time. By extracting these financial insights, this report will provide clear meaning into financial performance and offer insightful recommendations on how to optimize savings by reducing withdrawals.

----

## Data Source
The dataset was downloaded to google drive from my gmail in PDF format.
Sample of the PDF data:

![Screenshot](/Project/screenshot%20075222.png)

To automate my bank statement, I created a workflow in Zapier App that downloads the PDF attachment from my gmail to google drive, and then imported to Power Bi through PDF option in Get data. The data was cleaned and transformed in Power Query for further analysis.
Sample of the built workflow:

![Screenshot](/Project/Screenshot%20105425.png)

----

## Preparation Tools
  - Zapier: This was used to create a workflow for the gmail, goodle drive and Power BI, in other to achieve automation.
  - Power Query: This was used as a transformation and cleaning stage for the data before it was imported to the Power BI.
  - Power BI: This was used for analysis and visualization. A process achieved through DAX measures and visual tool  features in Power BI desktop.

----

## Data Processing
----
Data Transformation in Power Query: The following process was taken to prepare data for analysis:
  - Removing data duplicates
  - Removing errors
  - Standardization of data
  - Removing null values and blanks
  - Creating of Fact and dimension tables
    
    ![Screenshot](/Project/Screenshot%233138.png)

Data Modelling: A star schema relationship was created for the fact table and dimension table, and the data was permanently stored as import to enhance performance during refreshing.

![Screenshot](/Project/screenshot%20044827.png)

Data Preparation in Power BI: To further prepare the data for analysis I created the following:
   - Creating of Calender Table: This was created to facitate time-based analysis. First, the date column was created followed by the extraction of Year, Month, MonthNo and Quarter using the Date and Format function.
     
     ![Screenshot](/Project/Screenshot%20044606.png) 

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

![Screenshot](/Project/screenshot%20014850.png)

Using trigger and action features in Power BI and Zapier the dashboard will be automated on 7th of every month to enhance performance and aid accurate reading.


     







    




