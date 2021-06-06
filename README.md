# Pewlett-Hackard-Analysis
## Overview of the analysis:
Pewlett Hackard, a large company with thousands of employees, is looking ahead preparing for upcoming retirements by assessing the number of employees that could be entering the retirement age and can potentially result in several job vacancies. 

To prevent the high increase of retirement, Pewlett Hackard is introducing a new mentoring program for employees getting ready to retire. Instead of having a large chunk of the workforce retiring, with this mentoring program, experienced and successful employees will instead step back into a part-time role as a mentor to the newly hired workforce.

The purpose of the analysis is to determine the number of retiring employees per title and to identify employees who are eligible to participate in a mentorship program. Creating the employee retirement database will help future-proof Pewlett Hackard by providing analysis that can prepare for the "silver tsunami" as many current employees reach retirement age.

## Results:
1) A) Create a Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952, and December 31, 1955.
     - With queries using filters, joins and functions I created the Retirement Titles table.
        - [Retirement Titles](https://github.com/KristinaCastro/Pewlett-Hackard-Analysis/files/6604843/retirement_titles.csv)
     - When looking over the Retirement Titles data, we see that there are duplicate entries for some employees because they have switched titles throughout their years of employment at Pewlett Hackard.
![retirement_titles](https://user-images.githubusercontent.com/81998045/120938507-00e6d080-c6e1-11eb-8aeb-df94d6d1f286.png)

   B) To provide the most accurate information to prepare for the "silver tsunami" we need to further clean up our Retirement Titles list by removing the duplicates and keeping the most recent title of each employee. Using the DISTINCT ON statement, all duplicates were removed and the most up to date title for each employee is provided in the unique titles table.
      - [Unique Titles](https://github.com/KristinaCastro/Pewlett-Hackard-Analysis/files/6604854/unique_titles.csv)
![unique_titles](https://user-images.githubusercontent.com/81998045/120938706-33dd9400-c6e2-11eb-9035-68893aa30408.png)
 
   C) The last data list to create was the Retiring Titles table, which provides the number of retirement-age employees by most recent job title.
      - The Retiring titles table gives an overall view of vacancies per title level which will further help Pewlett Hackard prepare for potential job vacancies.
          - [Retiring Titles](https://github.com/KristinaCastro/Pewlett-Hackard-Analysis/files/6604858/retiring_titles.csv)
          
 ![retiring_titles](https://user-images.githubusercontent.com/81998045/120938713-45bf3700-c6e2-11eb-905e-2af0dde41bb8.png)

2) The Mentorship Eligibility Table helps to identifies all current employees who were born between January 1, 1965, and December 31, 1965, who are eligible for the mentorship program.
     - With queries using filters, joins and functions I created The Mentorship Eligibility Table
          - [Mentorship Eligibilty](https://github.com/KristinaCastro/Pewlett-Hackard-Analysis/files/6604885/mentorship_eligibilty.csv)
     - We can see from the data that there are currently 1,549 employees who are eligible to retire and participate in the mentorship program. This data is vital for Pewlett Hackard when planning for the future of the company and its employees.

![mentorship_eligibilty](https://user-images.githubusercontent.com/81998045/120939183-c2ebab80-c6e4-11eb-8842-74e93fd412b2.png)

## Summary
3) How many roles will need to be filled as the "silver tsunami" begins to make an impact? 
     - Using the Count() & Sum () functions, I created a query to calculate the total # of retirement eligible employees.
          - Overall Pewlett Hackard will have to plan to fill 90,398 internal roles.      
     - ![Screen Shot 2021-06-06 at 5 16 41 PM](https://user-images.githubusercontent.com/81998045/120940374-f92c2980-c6ea-11eb-9bda-b834e95a19f0.png)

 
2) Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
     - As we can see from the below tables, there are a total of 1,549 eligible to retire and to participate in the Mentorship program while we can see from the total employees that are eligible to retire by department exceeds the total legible mentors. So, there are not enough qualified, retirement-ready employees in the departments to mentor. 
     
<table>
  <tr>
    <td>Total Retirements by Department</td>
     <td>Mentorship Eligibilty totals</td>
  </tr>
  <tr>
     <td><img src="https://user-images.githubusercontent.com/81998045/120941823-f1708300-c6f2-11eb-8458-a3ad6de29a39.png" width=400 height=620></td>
     <td><img src="https://user-images.githubusercontent.com/81998045/120942531-93926a00-c6f7-11eb-90ab-bf13b678aace.png" width=400 height=620></td>
   </tr>
 </table>
          


 
          


   








