# Pewlett-Hackard-Analysis

## Overview 
We werre tasked by the Pewlett-Hackard management to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, we need to write a report that summarizes our analysis and helps prepare Pewlett-Hackard management for the “silver tsunami” as many current employees reach retirement age. We need to:



## Procedure & Results: 
In this project, we use QuickDBD and Schemas to design databases and writing intermediate-level SQL queries to answer important business questions for the company’s HR department. We also utilized PostreSQL a data base system to load, build, and host company data and pgAdmin and the result is a well-designed database with reporting capabilities. Initially, we imported 6 csv files containing employee details and job position information.

1.  For our first task we ran querries to :
2.  
    * create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955.
    * create a unique titles table without the duplicates.
    * Sort the Unique Titles table in ascending order by the employee number and descending order by the last date (i.e., to_date) of        the most recent title.
    The image below shows the query and the table:
    
    ![Screen Shot 2022-04-04 at 5 09 15 PM](https://user-images.githubusercontent.com/98566486/161632736-411ba920-a17c-46e2-8a2a-eac0e88940da.png)

    
    


The list of retiring employees including employee number, first name, last name, title for employees born in 1952.
The query returns 133,776 rows of data.
The table displays a list of employees who are going to retire in the next few years.
The list is a start, but we have a few employees who changed positions over the years and their records are showing up twice.
These records will become our retirement_titles table and csv.

Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?


 

