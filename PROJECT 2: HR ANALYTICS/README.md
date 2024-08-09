# HR ANALYTICS

###### It is highly recommended that the pbix file be downloaded for clearer details.

## Table of Contents
* [Acknowledgement](#Acknowledgement)
* [Analysis Objectives](#Analysis-Objectives)
* [Analysis Purpose](#Analysis-Purpose)
* [Technologies](#Technologies)
* [Analysis Results](#Analysis-Results)
* [Contents](#Contents)

## Acknowledgement
Obtaining HR data can be difficult, and HR professionals often find themselves less advanced in analytics and data visualization skills.

Dr. Carla Patalano and Dr. Rich Huebner at New England College of Business are the original authors of this dataset.

This is also a synthetic dataset.

LICENSE: CC-BY-NC-ND

## Analysis Objectives
Due to my great interest in HR, i decided to carry out this project in order to further my understanding and gain in-depth knowledge about this field.

## Analysis Purpose
I seek to answer several questions posed when analysing a typical workforce, including:
- Is there any relationship between who a person works for and their performance score?
- What is the overall diversity profile of the organization?
- What are our best recruiting sources if we want to ensure a diverse organization?
- Can we predict who is going to terminate? What level of accuracy can we achieve on this?
- Are there areas of the company where pay is not equitable?

These questions are raised from my knowledge and thought when conducting a basic analysis on firms' employees.

## Technologies
Project is created with:
* MS Excel 2016:
* MS PowerBI 
* MS SQL Server

## Analysis Results
I would deliver answers to aforementioned questions:
1. Is there any relationship between who a person works for and their performance score?
- Yes, there is. To answer this questions, i had used a treemap and a quadrant chart to analyse data. I conditioned that a manager should have at least 10 employees (approximation of 9.8 - company's average) working for him/her and their average performance score is at least 4 (approximation of 4.02 - company's average) in order to be shortlisted.
- Managers who satisfied the conditions are: Ketsia Liebig (Production - 4.06 - 16 employees), Kelly Spirea (Production - 4.13 - 15 employees), Brandon Miller (Production - 4.43 - 14 employees), David Stanley (Production - 4.0 - 14 employees), Peter Monroe (IT-IS - 4.0 - 12 employees), Elijah Gray (Production - 4.14 - 14 employees), Lynn Daneault (Sales - 4.18 - 11 employees), Janet King (IT-IS/Production/Admin Offices/Sales - 4.33 - 12 employees).
- You can try it by filtering data in the treemap chart and looking up performance score in the bar charts of 'HR Metrics', page 6/7 in my visualization.

2. What is the overall diversity profile of the organization?
- Most employees are White, coming off second being Black or African American, following by Asian, consisting of 61.08%, 25.12% and 9.85% respectively. The remaining proportion belongs to ones having two or more races and ones who are American Indian or Alaska Native.
- Most people at the company are US citizens, making up 96.14% while ones who are considered eligible citizens to work, yet are not US, make up only 3.38%. There is only 1 working staff who is a non-citizen. Most employees are also not Hispanic or Latino with 188 out of 207 employees meeting this condition. The majority of the workforce are also female, comprising a proportion of 56.04%.
- The data answering this question are visualized in page 4/7 in my visualization.

3. What are our best recruiting sources if we want to ensure a diverse organization?
- 'Indeed' has provided the company with all-of-races staffs employed during their history so far. Therefore, Indeed could be deemed the most diversified recruiting sources. 'LinkedIn, despite its great diversity, does not comprise any staff who is Hispanic. The same thing also occurs to 'Employee Referral' and 'Google Search' method of hiring, with the additional lack of American Indian or Alaska Native, two-or-more-races employees in the former, and Black and African American employees in the latter.
- Most employees hired from 'Indeed' are also US citizens, and this also occurs in other sources of recruitment as well.
- The data answering this question are visualized in page 4/7 in my visualization.

4. Are there areas of the company where pay is not equitable?
- Yes, there are. In fact, there are 3 areas, which are Production, IT/IS and Sales. These areas, in my opinion, have too great variety in salary range, respectively being 125K, 170K and 124K. This might lead to significant salary segregation and therefore, i am of opinion that pay is not equitable in these fields.
- The data answering this question are visualized in page 5/7 in my visualization.

5. Can we predict who is going to terminate? What level of accuracy can we achieve on this?
- Yes, we can. My assumptions for employees who are likely to terminate are noted in the visualization, you can view in page 7/7. For your information, my assumptions based on the analysis of terminated employees. I found that most terminated staff have salary below average, or to be precise, 79 out of 104 employees. More than a half of terminated employees, which is 54, are paid lower than their department's average salary. A notable detail is that 96 out of 104 terminated employees have a below-average performance score, which is an approximation of 4 (4.02). More than half of the staffs who work for Amy Dunn, Webster Butler & Kissy Sullivan also terminated their contract, which is also noteworthy.
- Therefore, I combine conditions as aforementioned to find likely termination, assuming a probability of 70%, as there is little connection among these conditions. I would analyse better and clearer given a better dataset and criteria, such as performance score and employee satisfaction being decimal number or of 'float' type.

## Contents

### The first page is a navigation pane.
![image](https://github.com/user-attachments/assets/26ffca20-80fe-43e0-97ac-7ab2c35b5ba9)

### The second page is an overview of the data analyzed.
![image](https://github.com/user-attachments/assets/32a69881-0703-417f-9598-dfbd2778f536)

Overall, the company has 207 employees, mostly recruited from 'Indeed' and have an average salary of 70.69K as well as an average age of 45.77. The median range of the former range from 65.9K to 93.09K, with the minimum being 63.35K and the maximum being 250K. 

'Production' department have the highest number of employees, wwith 126 staffs working in this department, followed by IT/IS, Sales, Admin Offices and Software Engineering, with 40, 26, 7 and 7 employees respectively.

The range of age at the company varies from 33 to 74 years old, with most people being of 41 to 59 years old group of age. The highest age recorded at the firm is 74, while the lowest is 33.

Most people, which is 177 out of 204 people, working at the company comes from MA, which is the abbreviation for Massachusetts. The majority of the workforce also come from the East side of the United States.

### The third page is a summarized evaluation of the workforce.
![image](https://github.com/user-attachments/assets/ceba7d6a-9a8a-4a23-a63e-1a4fcbc9705a)

The company witnesses an average new employee growth of 31.09% and a turnover rate of 22.29% (the turnover rate is calculated by dividing the number of employees who left by the average number of employees, then multiplying by 100). The peak number of employees hired and terminated along with the year they happened are 83 - 2011 and 23 - 2015 respectively. 

Out of 311 employees who is hired, 104 have terminated their contracts. The department who hires the most and also witnesses most termination is Production, and the least counterpart of its being Admin Offices. Executive, due to having too few employed, is not included in the analysis.

Most employees are employed as Production Technician I and II. The majority of the workforce are also recruited from Indeed, followed by LinkedIn and Google Search, making up the top 3 most popular recruitment source of the company.

There are multiple termination reasons, with the most common being having been offered another position.

### The fourth page visualized the overall diversity profile of the company.
![image](https://github.com/user-attachments/assets/79548f7b-c86d-49e9-aecb-6833303fcb06)

Most employees are White, coming off second being Black or African American, following by Asian, consisting of 61.08%, 25.12% and 9.85% respectively. The remaining proportion belongs to ones having two or more races and ones who are American Indian or Alaska Native.

Most people at the company are US citizens, making up 96.14% while ones who are considered eligible citizens to work, yet are not US, make up only 3.38%. There is only 1 working staff who is a non-citizen. Most employees are also not Hispanic or Latino with 188 out of 207 employees meeting this condition. The majority of the workforce are also female, comprising a proportion of 56.04%.

'Indeed' has provided the company with all-of-races staffs employed during their history so far. Therefore, Indeed could be deemed the most diversified recruiting sources. 'LinkedIn, despite its great diversity, does not comprise any staff who is Hispanic. The same thing also occurs to 'Employee Referral' and 'Google Search' method of hiring, with the additional lack of American Indian or Alaska Native, two-or-more-races employees in the former, and Black and African American employees in the latter.

Most employees hired from 'Indeed' are also US citizens, and this also occurs in other sources of recruitment as well.

### The fifth page is my analysis of the firm's departments.
![image](https://github.com/user-attachments/assets/09a1a054-73e9-4eb8-a328-700134b7aaeb)


### The sixth page is my development of HR Metrics.
![image](https://github.com/user-attachments/assets/a986441a-8b22-446e-a931-f4e3438a5e3c)



### The seventh page is my prediction for the workforce and termination assumption.
![image](https://github.com/user-attachments/assets/6b5e84d0-5e64-4a35-ae4f-56c97136bda4)


