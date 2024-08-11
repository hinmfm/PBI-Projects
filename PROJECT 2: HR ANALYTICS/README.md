# HR ANALYTICS

###### It is highly recommended that the pbix file be downloaded for clearer details. 
###### Due to file types being .csv, many files are disorganized when uploaded, i'm sorry for this.

## Table of Contents
* [Acknowledgement](#Acknowledgement)
* [Analysis Objectives](#Analysis-Objectives)
* [Analysis Purpose](#Analysis-Purpose)
* [Technologies](#Technologies)
* [Analysis Results](#Analysis-Results)
* [Contents](#Contents)
* [Ending](#Ending)

## Acknowledgement
Obtaining HR data can be difficult, and HR professionals often find themselves less advanced in analytics and data visualization skills. Therefore, Dr. Carla Patalano and Dr. Rich Huebner at New England College of Business, original authors, created their own HR-related dataset, which is used in one of our graduate MSHRM courses called HR Metrics and Analytics.

This is also a synthetic dataset. The CSV revolves around a fictitious company.

[The link to the dataset is given here](https://www.kaggle.com/datasets/rhuebner/human-resources-data-set)

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
- Managers who satisfied the conditions are: Ketsia Liebig (Production - 4.06 - 16 employees), Kelly Spirea (Production - 4.06 - 15 employees), Brandon Miller (Production - 4.19 - 14 employees), Elijah Gray (Production - 4.14 - 14 employees), Lynn Daneault (Sales - 4.0 - 11 employees), Janet King (IT-IS/Production/Admin Offices/Sales - 4.23 - 12 employees), Kissy Sullivan (Production - 4.10 - 10 employees)
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

Most employees are White, coming off second being Black or African American, followed by Asian, consisting of 61.08%, 25.12% and 9.85% respectively. The remaining proportion belongs to ones having two or more races and ones who are American Indian or Alaska Native.

Most people at the company are US citizens, making up 96.14% while ones who are considered eligible citizens to work, yet are not US, make up only 3.38%. There is only 1 working staff who is a non-citizen. Most employees are also not Hispanic or Latino with 188 out of 207 employees meeting this condition. The majority of the workforce are also female, comprising a proportion of 56.04%.

'Indeed' has provided the company with all-of-races staffs employed during their history so far. Therefore, Indeed could be deemed the most diversified recruiting sources. 'LinkedIn, despite its great diversity, does not comprise any staff who is Hispanic. The same thing also occurs to 'Employee Referral' and 'Google Search' method of hiring, with the additional lack of American Indian or Alaska Native, two-or-more-races employees in the former, and Black and African American employees in the latter.

Most employees hired from 'Indeed' are also US citizens, and this also occurs in other sources of recruitment as well.

### The fifth page is my analysis of the firm's departments.
![image](https://github.com/user-attachments/assets/09a1a054-73e9-4eb8-a328-700134b7aaeb)

The salary range at the company is 205K, with the lowest being 45K, the highest is 250K. The range is notably significant in several departments, they are Production, IT/IS and Sales, with their range respectively being 125K, 170K and 124K. 

Overall, the average satisfaction score of the company's staffs is 3.89. The department boasting highest average satisfaction score is IT/IS at 4.05, and the lowest is Admin Offices at 3.57. There are only 7 employees who have a satisfaction score below 3, yet a huge proportion of staffs at the firm are rather not satisfied, as reflected in 75 out of 204 only have a satisfaction score of 3. Despite this, people who have a greater satisfaction score, which is 4 and 5, is relatively high in size when compared to others, with 56 and 69 respectively.

(it is recommended that the slider be used due to great range and executive office be removed from the comparison due to too few employees)

In terms of Salary, the department with highest average salary is IT/IS with an average of 94512.08 and not much far behind is Software Engineering department, at 93262.57. The second lowest paid department is Admin Offices, with an average salary of 69088.85, yet this is of no comparison to the least paid, which is Production, as employees are only paid an average of 60419.26. The majority of people at the company also have the salary range below 80000, with 165 staffs and the second most-had range of salary is 80000 to 120000, with just 33 staffs, approximately one-fifth that of the former. The highest paid employees are Janet King, Jennifer Zamora and Debra Houlihan with their salary and department respectively are 250000 - executive office, 220450 - IT/IS and 180000 - Sales.

Production is the oldest department within the firm, having an average age of 46.19, followed by Sales, IT/IS, Software Engineering and Admin Offices. If executive office is mentioned, despite having only one executive, Janet King, the executive, is also among the oldest employees at 71 years old. The longest serving employees is Jack Torrence, who has stayed with the company since 2006 for a remarkable length of 13 years, given the final year in the dataset being 2018. 

Production is also the department with most employees, with 126 staffs, about 3-fold that of IT/IS which is the department with the second highest number of people. Followed by IT/IS are Sales, Admin Offices and Software Engineering with 26, 7 and 7 staffs respectively.

### The sixth page is my development of HR Metrics.
![image](https://github.com/user-attachments/assets/e1547a86-76c4-49c6-8bd3-eeef0d1d6f7a)

My developed HR Metrics only consisted of performance score, due to limitations of the original dataset. In this page, I analysed to find whether there is a correlation between salary and performance score, managers with most employees, average performance score of each department and top 5 of it among managers.

Overall, the company boasted an average performance score of 4.02, with the best manager being Eric Dougall, having his employees boast an average performance score of 4.25. Board of Directors are managers under whom employees are the paid the most. If BOD are excluded, Jennifer Zamora would replace, as employees working under her have an average salary of 133904.83.

From the quadrant chart, it is visible that there are certain managers who would guarantee a higher performance score, they are ones who are on the higher end of the x-axis division line. It is recommended that the .pbix file be opened at this point for further information. Self-criteria can also be added with filters. 

Brandon Miller, Kelly Spirea, Ketsia Liebig are managers with the most employees working under, all standing at 16. Followed by them are David Stanley and Elijah Gray with 15 and 14 staffs respectively. 

In terms of departments' average performance score, Software Engineering are seen to be effective, with an average of 4.14, followed by IT/IS at 4.08. Production, despite having the largest number of staffs working in, still manages to score an average of 4.05, which i deem remarkable. There is only one department with average performance score being below 4, which is Sales, as they score a mediocre 3.81. Eric Dougall, having only 4 employees, yet manages his employees well, shown in the average performance score of 4.25. Janet King comes in second, only 0.02 percentage points behind, and Simon Roup comes in third, 0.01 percentage point behind Janet.  Alex Sweetheart and Jennifer Zamora, both have 6 employees and an average score of 4.17, taking the final spots of top 5 managers with highest staffs' average performance score.

A scroller can also be found at the end of the page, showing the performance score of individual employee.

### The seventh page is my prediction for the workforce and termination assumption.
![image](https://github.com/user-attachments/assets/6b5e84d0-5e64-4a35-ae4f-56c97136bda4)

The first visible visuals in this page is the visualization of employee growth and forecast. It is forecasted that growth would last peaked in 2021 at 230.64% before undergoing a downward trend which saw a reduction in staff size. The confidence interval here is put at 95% and seasonality, at 10 points, as it is predicted that workforce would fluctuate greatly based on real-time historic events, such as Covid.

My assumptions based on the analysis of terminated employees. I found that most terminated staff have salary below average, or to be precise, 79 out of 104 employees. More than a half of terminated employees, which is 54, are paid lower than their department's average salary. A notable detail is that 96 out of 104 terminated employees have a below-average performance score, which is an approximation of 4 (4.02). More than half of the staffs who work for Amy Dunn, Webster Butler & Kissy Sullivan also terminated their contract, which is also noteworthy.

Therefore, I combine conditions as aforementioned to find likely termination, assuming a probability of 70%, as there is little connection among these conditions. I would analyse better and clearer given a better dataset and criteria, such as performance score and employee satisfaction being decimal number or of 'float' type.

## Ending

If you make it here, thank you very much. 
Under 4 years is the amount of time have i been a senior student at National Economics University, with a passion in data analytics and visualization, and also in English. 

Not gonna lie, I dream of nothing but to disseminate my knowledge to people and devote everything i could to the company i work for.
Gonna assume that this project has a total working time of 22 hours, yet flaws can still be found. 
And due to this, I am open to suggestions and advice.
Nonetheless, i express my gratitude towards ones who made it here.

Thank you very much.
