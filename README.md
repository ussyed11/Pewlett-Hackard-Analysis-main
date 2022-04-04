# Pewlett-Hackard-Analysis

## Overview 
We werre tasked by the Pewlett-Hackard management to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, we need to write a report that summarizes our analysis and helps prepare Pewlett-Hackard management for the “silver tsunami” as many current employees reach retirement age. We need to:



## Procedure & Results: 
In this project, we use QuickDBD and Schemas to design databases and writing intermediate-level SQL queries to answer important business questions for the company’s HR department. We also utilized PostreSQL a data base system to load, build, and host company data and pgAdmin and the result is a well-designed database with reporting capabilities. Initially, we imported 6 csv files containing employee details and job position information.

1.  For our first task we ran querries to :
 
    * create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955.
    * create a unique titles table without the duplicates.
    * Sort the Unique Titles table in ascending order by the employee number and descending order by the last date (i.e., to_date) of        the most recent title.
    The image below shows the query and the table:
    
    ![Screen Shot 2022-04-04 at 5 09 15 PM](https://user-images.githubusercontent.com/98566486/161632736-411ba920-a17c-46e2-8a2a-  eac0e88940da.png)
    
    * Then we wrote another query in the Employee_Database_challenge.sql file to retrieve the number of employees by their most recent       job title who are about to retire as shown in the image below:
    
    ![Screen Shot 2022-04-04 at 5 14 12 PM](https://user-images.githubusercontent.com/98566486/161633261-59cfeec4-480c-4b36-9be1-258bec1c003b.png)
    
 2. For our second task we ran and executed a query to create a Mentorship Eligibility table that holds the employees who are eligible to participate in a mentorship program.

![Screen Shot 2022-04-04 at 5 19 37 PM](https://user-images.githubusercontent.com/98566486/161634024-aa308bab-e07a-4942-98d5-1f8ae34cf4e2.png)

## Summary: 

Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?


 

