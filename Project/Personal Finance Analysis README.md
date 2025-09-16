# PERSONAL FINANCE ANALYSIS
----
# Table of Contents
----
- [Financial Overview](#financial-overview)
- [Data Source](#data-source)
- [Preparation Tools](#preparation-tools)
- [Data Processing](#data-processing)
- [Skills Demonstrated](#skills-demonstrated)
- [Objectives](#objectives)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Insights](#insights)
- [Recommendation](#recommendation)
- [Dashboard Interaction](https://app.powerbi.com/groups/me/list?experience=power-bi)

----

## Financial Overview
This report presents a comprehensive overview analysis of my personal bank statement from Jan 2025 to Sept 2025, based on the provided dataset. The primary objective of this analysis is to automate workflow for my bank statament in other to monitor my personal finance cash flow over a period of time. By extracting these financial insights, this report will provide clear meaning into financial performance and offer insightful recommendations on how to optimize savings by reducing withdrawals.

----

## Data Source
The dataset was downloaded to google drive from my gmail in PDF format.
Sample of the PDF data:

![Screenshot](/Project/screenshot%20075222.png)

To automate my bank statement, I created a workflow in Zapier App that downloads the PDF attachment from my gmail to google drive, and then imported to Power Bi through PDF option in Get data. The data was cleaned and transformed in Power Query for further analysis.
Sample of the Power Query data:

![Screenshot](/Project/screenshot%20050651.png)

----

## PREPARATION TOOLS
  - Power Query: This was used as a transformation and cleaning stage for the data before it was imported to the Power BI.
  - Power BI: This was used for analysis and visualization. A process achieved through DAX measures and visual tool  features in Power BI desktop.

----

## DATA PROCESSING
----
Data Transformation in Power Query: The following process was taken to prepare data for analysis:
  - Removing data duplicates
  - Removing errors
  - Standardization of data
  - Removing null values and blanks
  - Creating of Fact and dimension tables
    
  ![Screenshot](/Project/screenshot%20050651.png)

Data Modelling: A star schema relationship was created for the fact table and dimensional table, and the data was permanently stored as import to enhance performance during refreshing.

  ![Screenshot](/Project/screenshot%20044827.png)

Data Preparation in Power BI: To further prepare the data for analysis I created the following:
   - Creating of Calender Table: This was created to facitate time-based analysis. First, the date column was created followed by the extraction of Year, Month, MonthNo and Qurater using the Date and Format function.
     
   ![Screenshot](/Project/screenshot%20044827.png)  




