
# HR Analytical Dashboard

### Dashboard Link : https://geuac-my.sharepoint.com/:u:/r/personal/21102061_geu_ac_in/Documents/HR.Analytical.pbix?csf=1&web=1&e=hQjYHR

## Problem Statement

This dashboard provides HR managers with valuable insights into their employees, helping them better understand their satisfaction levels and overall well-being. By analyzing various ratings, HR managers can assess employees' mental health conditions, work-life balance, and performance levels.

Key highlights include:

Employee Satisfaction:
A total of 289 employees rated their job satisfaction as 1 out of 4, underscoring the urgent need for targeted strategies to enhance morale and engagement.

Departmental Insights:
Among the HR, Sales, and Research & Development departments, the Research & Development department stands out with the highest number of dissatisfied employees. Specifically, 192 employees from this department have given a 1 out of 4 rating for job satisfaction.

By leveraging these insights, HR managers can take proactive measures to address critical challenges, foster a positive and supportive workplace culture, and drive improvements in employee satisfaction and overall performance.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : To calculate the number of fresher, experienced, and highly experienced employees, we used DAX function and create a pie chart.
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data includes attrition, we created a separate page to display department, job role, and business travel details for employees who have left the company.
- Step 8 : Visual filters (Slicers) were added for six fields: "Age", "Gender", "Department", "Education", "Job Role", and "Attrition".
- Step 9 : One card visual was added to the dashboard to represent the total number of employees.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into calculation.
           
           Although, by default, while calculating blank values are ignored.
- Step 10 : Three bar chart was also added to the report design area representing the number of job role, education and attrition.  
- Step 11 : Ratings data was used in filters according to specific requirements.
- Step 12 : In the report view, under the insert tab, one text boxes were added , in which name of the dashboard was mentioned.
- Step 13 : In the report view, under the insert tab, using shapes option from elements group a square was inserted & similarly using image option HR analyzing logo was added to the report design area. 

        
- Step 15 : In addition a measure was created to find total count of customers.

Following DAX expression was written for the same,
        
        Total Employees = COUNT
        ('HR_Analytics_Data[1]'[Employee Count])
        
A card visual was used to represent count of customers.

![Screenshot 2024-12-16 160052](https://github.com/user-attachments/assets/e3863def-f13b-492d-b43b-ec8581d27ab6)




        

# Snapshot of Dashboard (Power BI Service)

![Screenshot 2024-12-16 160632](https://github.com/user-attachments/assets/abf36915-1041-425a-990b-0eeaeb497992)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Screenshot 2024-12-16 160632](https://github.com/user-attachments/assets/abf36915-1041-425a-990b-0eeaeb497992)


I have created separate pages based on age, employee and attrition to view the number of employees under different headings.

# Insights

All report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Employees = 1470

    Number of unsatisfied employees (Male) = 170
    Number of unsatisfied employees (Female) = 119
   
### [2] Average Ratings

    a) Avg Environment satisfaction - 2.74/4
    b) Avg Work Life Balance - 2.77/4
    c) Avg Job satifaction - 1/4
    
    while calculating average rating, null values have been ignored as they were not relevant.
    

 ### [3] Some other insights
 
 ### Age Group
 
 2.1)  8.37 % customers belong to '18-25' age group.
 
 2.2)  60 % customers belong to '26-40' age group.
 
 2.3)  31.63 % customers belong to '41-60' age group.
 
         thus, maximum customers belong to '26-40' age group.
         

Displaying # HR_Analytical-Dashboard.md.txt.
