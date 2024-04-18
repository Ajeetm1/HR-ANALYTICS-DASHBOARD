# HR-ANALYTICS-DASHBOARD

# HR Analytics Dashboard



**Objective:**
This Power BI project is all about figuring out why employees are leaving the company. By looking at things like who's leaving, why were they all not happy
with their jobs , and how engaged they are, we want to spot patterns and reasons for attrition which is not good for company. This dashboard provides insights of the attrition of an organization which helps the HR team for their further analysis. 

## Steps followed:
Download the dataset from here (https://github.com/Ajeetm1/HR-ANALYTICS-DASHBOARD/blob/main/HR_Analytics.csv)

1. Data Gathering:

Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.

2. Data cleaning:

Cleaning is done by removing empty column, removing duplicates, errors etc.
Replacing values in column with proper values and naming.
Detecting data type of every column, using the auto detect data type function in Power query editor.

3. Data processing:

In the Power Query editor, creating new column called "AttritionCount" by using conditional column feature in add column which is created on the basis of certain condition like (IF attrition = 'Yes' then 1, Else 0).
This new column is further used for creating different KPI's and charts.Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = SUM([AttritionCount]))/SUM([Employeecount])) in %.

4. Data analysis:

Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant visualizations.
These tools are utilized to gain insights and present data in a comprehensive and easily understandable manner.


## Key Questions of the Dashboard : -
1. What is the Total Employee Count ?
2. What is the employee's Average Age & Average Salary ?
3. What is the Attrition Count of men and women ?
4. What is employees Working years at the Company ?
5. Which Department has maximum employee ?
6. What is the Gender distribution ?
7. Which Education Field has maximum employees ?


## Key Insights Summary:
1. Total Employees: The organization has grown significantly, currently employing 1470 individuals, indicating substantial growth and scale.

2. Attrition Analysis: A total of 237 employees left the organization. Among them, 150 were male, and 87 were female, indicating a higher attrition rate among males.

3. Departmental Attrition: The Research and Development Department experienced the highest attrition  133 employee, suggesting potential areas for improvement in employee retention strategies in this department.

4. Education Field Impact: Employees in the life sciences field had the highest attrition rate, emphasizing the need to address retention challenges in this specific area.

5. Job Role Affected: The sales role had the highest attrition rate, indicating a need for focused retention efforts in this department to reduce turnover.

6. Education field wise Attrition: The attrition rate of Life sciences is 37.6% which is maximum among the other education.

7. Attrition Rate by Gender for Different Age Group: The attrition count among the age group of 26-35 years 116 which is maximum among the other age groups.



