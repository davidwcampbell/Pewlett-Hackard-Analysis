# Pewlett-Hackard-Analysis

## Overview
This analysis was completed to help Pewlett Hackard prepare for the "silver tsunami". The "silver tsunami" refers to the fact that many people in the Baby Boomer generation will be retiring soon. Baby Boomers make up a considerable amount of the company's workforce and they want to be prepared for the future. Pewlett Hackard also decided they should begin a mentoring program within the company where experienced employees could help those with less experience assume leadership roles as those were vacated by retirees. The analysis will identify how many roles need to be filled due to the "silver tsunami" and also identify employess that are going to retire that could possibly mentor other employees. 

## Analysis
Pewlett Hackard provided six files of company data to perform the analysis: Departments, Employees, Department Managers, Department Employees, Salaries, and Titles. These individual files contain data we need to answer the questions posed. It was decided that an SQL database would be the best way to analyze the data. We began our analysis by creating an ERD (entity relationship diagram) for the files that defines the relationship between the tables. The image below shows each file, the headers for the columns of data in the file, the type of each field, and the relationship between the individual tables.

![](https://github.com/davidwcampbell/Pewlett-Hackard-Analysis/blob/master/EmployeeDB.png)

After the ERD was complete we imported data into PostgreSQL tables that we had defined using PGadmin. PGadmin allowed us to easily query, join, and group the data to create new tables that would answer our questions. 

## Results
The analysis shows that there are 41,380 employees that are eligible to retire soon. We created a file that shows details of this by employee, title, and salary. The two titles with the largest number is Senior Engineer with 15,600.  Senior Staff was a close second with 14,735. There are files in the analysis that show this data in detail for the seven titles with retirement eligible employees. We also identified 1,549 employees that are potential mentors.

Additional analysis would be helpful to determine the number of employees that were intending to retire and when. A simple survey could collect this data from employees and added to this analysis. With this data, Pewlett Hackard would be better able to prepare a strategy for the future.
