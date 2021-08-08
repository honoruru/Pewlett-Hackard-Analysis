# Pewlett Hackard Analysis

## Project Overview

The purpose of this analysis is to assess Pewlett Hackard’s (PH) readiness to confront the wave of employees that are reaching retirement.  To do this we will determine the number of retiring employees (by title) and identify employees who are eligible to participate in a to-be-developed mentorship program.

## Results

The team created two lists:
1.	Number of Employees Retiring
2.	List of Employees Eligible for the Mentorship Program

Upon completing the lists, analysis showed the following:

1.	The list of Number of Employees Retiring showed that 72,458 were nearing retirement age.  For the purpose of the analysis, retirement age was defined as ages 65 to 68. Not surprisingly, the largest number of potential retirements were at the Senior Engineer and Senior Staff positions.  It was also noted that two of the nine Managers were of retirement age. See query at Exhibit 1.

<img src="https://github.com/honoruru/Pewlett-Hackard-Analysis/blob/main/Challenge%20Images/Deliverable%201%20Output.PNG" width="300" height="300" />

2.	Still, the list of Number of Employees Retiring the list was not as informative as one would need it to be to prepare for the potential wave of retiring employees.  For instance, it did not identify which, if any, department was more vulnerable due to a disproportional number of retiring employees in any given job function. 

3.	The List of Employees Eligible for the Mentorship Program provided 1,549 names and titles of employee born in 1965, i.e., 55-56 years of age.  The age range for potential mentors was recommended by management.  The list also included the individuals’ start date at their current position.  This may not capture an individual’s actual years of experience, however, is still useful. See query at Exhibit 2.

(Deliverable 2 Output.PNG)
<img src="https://github.com/honoruru/Pewlett-Hackard-Analysis/blob/main/Challenge%20Images/Deliverable%202%20Output.PNG" width="300" height="300" />
 

4.	The 1,549 individuals on the List of Employees Eligible for the Mentorship Program appeared inadequate to mentor the remaining employees after potentially 72,458 began to retire over the next three years.  As mentioned above, it was unknown if any departments were disproportionally impacted.  The count of Employees Eligible for the Mentorship is displayed below in an Excel pivot table summary.

(Deliverable 2 Excel totals.PNG)
 


## Summary
As noted, 72,458 total roles would likely need to be filled as PH’s workforce aged.  
To assess whether any department was disproportionally impacted, tables were developed that broke down all current and potentially retiring employees by title and department.  See queries at Exhibit 3.

Comparing the results of the queries using Excel, it was determined that, remarkably (#blessed), every position in every department was equally impacted with around 30% potentially retiring.  
The question remained whether there were enough qualified employees in the departments to mentor the next generation of PH employees.  The initial tables provided only the number of potential members by job title.  Again, additional tables were developed to break down the number of potential mentors by title and department.  See queries at Exhibit 4.
Our mentorship analysis is illustrated below in an excerpt from the Excel workbook title_compare_PIVOT.xlsx located in the Data folder.
(titles_compare_PIVOT excerpt.PNG)
 
This analysis shows that the ratio for mentor-to-non-retiring employees varies among departments.  However, the information is useful for the development of the mentorship program.

With the plan to develop a table to determine if the number of potential mentors could be expanded beyond employees aged 55-56, the team took a closer look at the employees.csv data initially provided to the team.  Embarrassingly, the team realized that, based on the data, no current employee was born after 2/1/1965 nor hired after 1/23/2000.  See queries at Exhibit 5.
(active_employee_pivot_img.PNG)
 

A quick visit to the employee lunchroom noted that there were numerous 30-somethings enjoying their break.  We fell victim to our cardinal rule by not reviewing the raw data thoroughly before investing efforts in analyzing. While our conclusions were rendered questionable based on our data’s incompleteness, solace is taken in that once we obtained accurate and complete data, our queries would be ready to be applied.  

## EXHIBITS

 
# Exhibit 1
(Deliverable 1 FIXED.PNG)
 
 
# Exhibit 2
(Deliverable 2.PNG)
 

 
# Exhibit 3
(Titles_compare code.pdf)
     
 

(Create title_compare pgAdmin.PNG)
 
 
# Exhibit 4
(Deliverable 2.PNG)
 
 
# Exhibit 5
(active_employee code.PNG)
 
