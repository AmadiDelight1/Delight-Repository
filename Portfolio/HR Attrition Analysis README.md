# HR EMPLOYEE ATTRITION ANALYSIS
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

Employee attrition remains one of the biggest challenges for organizations.The HR Attrition Analytics dashboard provides a comprehensive analysis of employee behavior, turn over, satisfaction and demographics.The dashboard helps HR teams uncover root causes of attrition and make evidence based decisions that support retention and workforce planning.

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
The 31% attrition rate among employees with poor balance suggests workload overload, poor scheduling, lack of flexible work arrangements and insufficient HR monitoring of burnout.

----

How deos Job Satisfaction Rate affect Attrition?:

![Screenshot](/images/Screenshot%20093824.png)

This visual shows comparison of attrition between “Yes” (left) and “No” (stayed) groups across satisfaction levels.

Key Takeaways:
Even employees with Great satisfaction leave. This implies:
- Satisfaction ≠ engagement
- Engagement ≠ retention
Other hidden drivers may include:
- Compensation disparities
- Career stagnation
- Micromanagement
- Poor leadership communication
  
----

How many Employees left each Department?

![Screenshot](/images/Screenshot%20093840.png)

The visual shows Employees who left by department:
- R&D: 133
- Sales: 92
- HR: 12

Key Takeaway:
R&D has the highest attrition likely due to workload pressure, skill competition and limited career growth paths. Also most R&D staff fall into the 25–34 range which is the highest attrition age group.

----

Age Group vs Attrition Count

![Screenshot](/images/Screenshot%20093855.png)

This visual show the following:
- Under 25 → 38
- 25–34 → 112 (highest)
- 35–44 → 51
- 45–54 → 25
- 55+ → 11

Key Takeaway:
Employees aged 25–34 show the highest turnover due to:
- Career-switching
- Desire for rapid growth
- Competitive salary expectations
- Relocation flexibility

----

Marital Status vs Attrition Rate

![Screenshot](/images/Screenshot%20093917.png)

This visual show the following:
- Married → 51%
- Single → 35%
- Divorced → 14%

Key Takeaway:
From the dashboard visuals, married employees show the highest attrition rate compared to single and divorced employees. This may happen due to:
- Higher Financial Pressure
- Work–Life Balance Challenges
- Limited Career Progression

----

## Recommendations

----

Improve Work–Life Balance:
- Introduce flexible working hours or hybrid options.
- Review workload distribution across departments.
- Implement wellness and burnout-prevention programs.

Strengthen Compensation & Benefits
- Benchmark salaries against industry standards.
- Offer targeted salary adjustments for mid-career employees.
- Introduce performance bonuses tied to retention.

Enhance Career Growth Opportunities
- Create transparent promotion paths and development plans.
- Sponsor role-specific training or certifications.
- Introduce mentorship programs for mid-level employees.

Reduce Attrition in High-Impact Departments (R&D)
- Conduct stay interviews to understand high turnover drivers.
- Assign manageable project loads and improve manager employee relationships.
- Offer project-completion incentives or recognition programs.

Support Married & Mid-Career Employees
- Provide family-friendly benefits (healthcare, childcare support, leave).
- Create flexible policies for parents or caregivers.
- Offer career progression programs tailored for experienced employees.

----

## Dashboard

----

![Screenshot](/images/Screenshot%20235549.png)

----

## Conclusion

----

This HR Analytics Dashboard provides a clear, data-driven view of employee attrition patterns across departments, age groups, marital status and satisfaction metrics. The analysis reveals that married and mid-career employees show the highest attrition, with the R&D department being the most impacted. Indicator such as work–life balance strongly influence employee decisions to leave.

The recommendations provided offer a structured approach for HR teams to address these issues focusing on improving work–life balance, strengthening compensation, enhancing career development and creating better support systems for experienced employees. By implementing these actions, organizations can significantly reduce turnover, improve employee engagement and build a more stable and productive workforce.

Thank You!

Let's connect
delightamadi.carrd.com
