# OLYMPICS DASHBOARD [Sports Analytics](Interactive Dashboard Built with Power BI)
## Project Objective
The objective of this HR Analytics dashboard is to analyze employee attrition and understand the factors that contribute to it. This includes examining patterns and trends in attrition across various dimensions such as age group, salary slabs, education fields, job roles, and gender. Key KPIs like Attrition Rate, Average Age, Average Salary, and Average Tenure are tracked to identify high-risk segments and support strategic HR decisions. The insights derived aim to help organizations reduce employee turnover, improve workforce planning, and enhance employee retention strategies.

## Dataset used
- <a href="https://github.com/aditya-kumaarr/power_bi_Hr_analytics_p1/blob/main/HR_Analytics.csv">Dataset</a>

## Questions (KPIs)
- What is the overall employee attrition rate?
- What is the average age of employees?
- What is the average monthly salary of employees?
- What is the average years of experience (tenure) in the organization?
- Which job roles have the highest attrition rates?
- What is the gender-wise distribution of attrition?
- Which education field has the most attrition cases?
- How does attrition vary across different age groups?
- Which marital status group has the highest attrition?
- What are the attrition patterns across various salary slabs?

##Dashboard Interaction <a href="https://github.com/aditya-kumaarr/power_bi_Hr_analytics_p1/blob/main/assets/dashboard.png">View Dashboard</a>

## Process
- Verified data for missing values and anomalies using Power BI’s Power Query Editor and handled inconsistencies.
- Ensured data consistency by formatting columns appropriately and standardizing data types.
- Created Attrition_Count column using DAX in the data modeling section:
Assigned a value of 1 for each row where Attrition = "Yes" and 0 otherwise.
![Screenshot (495)](https://github.com/aditya-kumaarr/power_bi_Hr_analytics_p1/blob/main/assets/attrition_count.png)
- Created Attrition_Rate measure using DAX in the data modeling section:
Calculated as the total Attrition_Count divided by the total EmployeeCount.
![Screenshot (495)](https://github.com/aditya-kumaarr/power_bi_Hr_analytics_p1/blob/main/assets/attrition_rate.png)
- Designed interactive visuals (cards, bar charts, pie charts) to answer key business questions.
- Integrated all visuals into a single dashboard and used slicers to make the dashboard dynamic and user-friendly.
  
## Dashboard

![Screenshot (495)](https://github.com/aditya-kumaarr/power_bi_Hr_analytics_p1/blob/main/assets/dashboard.png)

## Project Insight
- Overall Attrition Rate: The dashboard shows an attrition rate of 16.1%, indicating that a noticeable proportion of employees are leaving the organization.
- Gender-wise Attrition: Female employees have a slightly higher attrition count than males. This could point toward a need to explore gender-based engagement or policy reviews.
-	Age Factor: The majority of employees who left were between 26 to 35 years old, which suggests mid-career professionals may be more likely to resign, possibly for better opportunities or dissatisfaction.
-	Job Role Influence: Job roles like Sales Representative and Laboratory Technician contribute significantly to overall attrition. These roles might be facing issues like burnout, workload, or limited growth.
-	Marital Status: Single employees show a noticeably higher attrition rate compared to married employees. This could be due to increased job-hopping among early-career individuals or lifestyle flexibility.
-	Monthly Income Impact: A large portion of attrition appears to occur in employees with monthly income between 2,000 and 5,000, suggesting salary dissatisfaction could be a factor.
-	Distance from Home: Employees living closer to the workplace (0–10 km) surprisingly had higher attrition counts. This could indicate issues unrelated to commute, like culture fit or management concerns.
-	Departmental Breakdown: The Research & Development department had the highest number of resignations. This could warrant deeper analysis into project loads, management style, or development opportunities.

## Final Conclusion
- This HR Analytics Dashboard project was designed to help organizations understand employee attrition trends through data-driven insights. Using Power BI, we analyzed key HR metrics such as Attrition Rate, Department-wise Attrition, Job Role Impact, and Demographic Influence on attrition.
- The dashboard simplifies complex HR data into clear and actionable visuals, empowering decision-makers to identify areas of concern and develop strategies to improve employee retention. The ability to slice data across Age, Department, and Job Role makes it a dynamic tool for in-depth HR analysis.
- This project not only demonstrates strong skills in Power BI and data storytelling, but also showcases the ability to translate raw data into business insights, which is essential for any data analytics role.

## If you'd like to connect or collaborate on data projects, feel free to reach out on: 
• **LinkedIn**: https://www.linkedin.com/in/aditya-kumar-4a175635b/
• **Email**: adityaakumaarr@gmail.com

