# HR Analytics
PowerBI dashborad with HR metrics and data for analysis

## Content
- [Project Description](#project-description)
- [Organization](#organization)
- [Data Processing](#data-processing)

# Project Description
The objective of this project is to create a dashboard to visualize in an easy and agile way the information coming from a database of a human resources department. 

Managing the data of a company with many employees can be difficult to understand and interpret because the information can be mixed and having a global perspective is becoming more and more complicated.  

Therefore, in order to be able to interpret the data correctly, several dashboards were created for different purposes so the information could be contextualized and organized according to distinct subjects. 

# Organization

Employee management dashboard: 
The first screen consists of a set of 6 visualizations that summarize the overall picture of the company, and how the distribution of employees is in relation to each of the department's objectives.
The first row contains the information related to the objectives: 
 leveling, number of promotions, number of attrition, and gender equity in leadership levels. 
And in the second row are the graphs showing the overall status of the company in terms of employees by department, education field by job level, and salary by role.

1. Performance satisfaction:
In order to visualize the performance of the department, a dashboard was included just to visualize the results of the satisfaction surveys of all employees. 

These results include job satisfaction, work environment, and relationship, as well as involvement and work/life balance. 

All results are displayed divided by gender and can be filtered by department, the field of study, and whether employees work overtime. 

2. Salary analysis 
To finish including the financial part, fundamental in any human resources department, a table was made to analyze only graphs related to salary. 

This includes the company's monthly payroll expenses, average salary by gender, average hourly pay by the level of education, monthly salary by time in the role, by field of study, and by type of position. 

Here, as in the previous dashboard, all charts can be filtered by department. 

# Data Processing
To visualize this information, the data was exported in CSV format to Power BI. Within the platform, adjustments were made to the data format in order to be able to perform mathematical operations on the numerical information. 

Additionally, in order to better manage the information and visualizations, a new table was created with all the basic measures that will allow extracting factual data from the original report (total number of employees, total number and percentage of men and women, number of employees to be promoted, total attrition).

These new calculated measures will be defined using Data Analysis Expressions (DAX) logic. 


