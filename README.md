# Pewlett-Hackard-Analysis
## Overview of the Analysis
Pewlett_Hackard(PH) is facing a *'silver tsunami'*. To rise the challenge, PH need to get well prepared. The analysis is target on retirement-age employees.
  1. Use `INNER JOIN` to combine *employees* and *titles* tables. 
     Then retrieve employees' information who were born in 1952 through 1955 and currently working in the company.
  2. Use `DISTINCT ON` and `ORDER BY` to get the retiring employees' current position.
  3. Use `COUNT` and `GROUP BY` to sort and count the retiring employees by department.
  4. Use `INNER JOIN` to retrieve current employees' personal information, who were born in 1965, and their titles. These employees are eligible for mentorship.
  
## Results
- [Retirement Titles](https://github.com/CelineWW/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv) table holds all the titles of employees who were born between 1952 and 1955. Since some of employees has been taken different positions in the company, employees' number and name are dupulicate. Table head is shown as below:

![Retirement Titles table](https://user-images.githubusercontent.com/105877888/178130790-120d2fda-a960-42ac-a686-887adf2c0c84.PNG)

- [Unique Titles](https://github.com/CelineWW/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv) table holds the most recent title of employees from Retirement Titles table. Each employee in the table is unique. Table head is shown as below:

![Unique Titles table](https://user-images.githubusercontent.com/105877888/178130793-32c559eb-9b45-4120-bb92-46572e1f3fe2.PNG)

- [Retiring Titles](https://github.com/CelineWW/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv) table holds the number of retirement-age employees by their most recent title. The caculation was based on Unique Titles table. Table is shown as below:

![Retiring Titles table](https://user-images.githubusercontent.com/105877888/178130810-6e533cd0-4d54-4a57-8da8-b51af4564507.PNG)

- [Mentorship Eligibility](https://github.com/CelineWW/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv) table holds mentorship-eligible employees. These current employees were born in 1965. Table head is shown as below:

![Mentorship Eligibility table](https://user-images.githubusercontent.com/105877888/178130932-72dc8ca2-daa8-49a7-90c0-9dc120f0fde2.PNG)


 



2. Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.
Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
Results:

There is a bulleted list with four major points from the two analysis deliverables. (6 pt)



Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Summary:

The summary addresses the two questions and contains two additional queries or tables that may provide more insight. (5 pt)
