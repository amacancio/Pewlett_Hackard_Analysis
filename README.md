# Pewlett_Hackard_Analysis

## Overview of the Analysis
The purpose of the analysis was to help Bobby's manager prepare for the "silver tsunami" by determining the number of retiring employees per title, and identifying employees who are eligible to participate in a mentorship program.

## Results

<ul>
  <li><b>Step 1:</b> Create a table identifying the employee number, first name, last name, title, from date, and to date of each employee whose birthdate fell between 1952 and 1955.</li>
  
  <br>
  
![Retirement_titles table query](https://user-images.githubusercontent.com/94088129/162015960-8a2d0cf7-d22e-45ef-84e7-aeccfbc019b6.png)
  
  <br>
  
<img width="696" alt="Retirement_titles table image" src="https://user-images.githubusercontent.com/94088129/162015981-52fea582-49da-4c06-8c70-9b99a3dff2e9.png">
  
  <br>
  <br>

  <li><b>Step 2:</b> Use the DISTINCT ON statement to retrieve the first occurence of the employee number, excluding those employees who had already the company, and use ORDER BY to sort the list in ascending order by the employee number and descending order by the last date (i.e., to_date) of the most recent title.</li>
  
  <br>
  
  ![Unique_titles table query](https://user-images.githubusercontent.com/94088129/162016596-f0e542fb-389b-478e-a575-207632448cca.png)
  
  <br>
  
<img width="528" alt="Unique_titles table image" src="https://user-images.githubusercontent.com/94088129/162016614-9f58be26-46e7-4313-8445-ea6dabbaf019.png">
  
  <br>
  <br>

  <li><b>Step 3:</b> Use the COUNT statement to retrieve the number of employees by most recent title who are about to retire.</li>
  
  <br>
  
  ![Retiring_titles table query](https://user-images.githubusercontent.com/94088129/162017148-4b86b70a-5f16-42b5-90b1-ec230e5eb48f.png)
  
  <br>
  
<img width="252" alt="Retiring_titles table image" src="https://user-images.githubusercontent.com/94088129/162017165-b3d18ca9-06a6-4769-b1fd-8e40c6eda93f.png">

  <br>
  <br>
  
  <li><b>Step 4:</b> Use the DISTINCT ON and INNER JOIN statements to retrieve the information of employees who are still employed with the company and eligible for retirement, as well as the ORDER BY statement to organize the table by employee number.</li>
  
  <br>
  
  ![Mentorship_eligibility table query](https://user-images.githubusercontent.com/94088129/162018123-e0758d5e-f352-4324-b6be-92c28acdaa2b.png)
  
  <br>
  
<img width="786" alt="Mentorship_eligibility table image" src="https://user-images.githubusercontent.com/94088129/162018139-98e13495-07b3-4af8-9355-80ac1ce69704.png">

</ul>
  
## Summary

<ol>
  <li>How many roles will need to be filled as the "silver tsunami" begins to make an impact?</li>
    The total number of roles that will need to be filled is 72,458.
   
  <li>Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?</li>
    

















