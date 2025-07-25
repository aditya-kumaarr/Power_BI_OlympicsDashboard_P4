# OLYMPICS DASHBOARD (Interactive Dashboard Built with Power BI)
[Sports Analytics]

## Project Objective
The objective of this Olympics 2024 dashboard is to provide an interactive visual analysis of the Paris 2024 Olympic Games. The goal is to explore athlete and country performances, medal distributions, and historical trends. By examining dimensions such as countries, athlete demographics, medal types, and sporting disciplines, the dashboard uncovers patterns and provides actionable insights for analysts, enthusiasts, and sports professionals. Key KPIs include medal tallies, gold medal counts, athlete age distributions, gender splits, and performance trends across editions. These insights enable data-driven storytelling, highlight emerging talents, and reveal factors contributing to Olympic success.

## Dataset used
- <a href="https://github.com/aditya-kumaarr/power_bi_Hr_analytics_p1/blob/main/HR_Analytics.csv">Dataset</a>

## Questions (KPIs)
- What is the overall medal tally for each country?
- Which countries dominated in gold, silver, and bronze medals?
- How is medal distribution by sport?
- What is the gender-wise participation and medal split?
- Who are the top athletes and standout performances?
- Which age groups achieved the most success?
- What historic medal trends stand out across past Olympic editions?
- How do countries' performances compare over time?
- Which sports or nations saw the greatest improvements in Paris 2024?

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
-	Global Medal Landscape: The dashboard reveals in fine detail how the top-performing countries cemented their positions, with clear visualizations of overall and gold medal leaders. It highlights not only dominant teams like the United States, China, and host nation France, but also spotlights emerging nations that made significant medal gains compared to previous Olympics. Heat maps and leaderboards make it easy to analyze how traditional powerhouses have maintained their edge, while animations showcase breakthrough performances from smaller or less expected states.
-	Sport-by-Sport Analysis: Through interactive filtering, the dashboard uncovers which specific sports contributed most to each country’s medal haul. This provides actionable intelligence for national committees keen to identify the disciplines where investment returns are highest. The data illustrates, for example, China’s technical excellence in diving, the USA’s track dominance, and how new disciplines like skateboarding and sport climbing reshaped the medal table distribution in Paris 2024.
-	Athlete Demographics and Performance: 
A comprehensive demographic breakdown points to evolving trends in Olympic participation:
• The age visualization reveals the typical age range for medal-winning athletes by sport and gender, highlighting both prodigies and veterans who defied expectations.
• Gender distribution charts show significant progress toward parity across multiple disciplines, with interactive insights into which events saw the closest balance in participation and podium finishes.
• Drilldowns reveal the most decorated athletes, enabling deeper exploration of multi-medal winners and standout debut performers.
- Historical and Comparative Trends:
The dashboard’s time-slider allows users to explore the evolution of the Olympics, comparing current trends against a rich backdrop of historical data. This empowers users to investigate patterns such as:
• Which nations have recently surged or faced decline in medal counts.
• The impact of new and discontinued sports on medal spreads.
• How the introduction of gender parity initiatives changed the competitive landscape.
- Equity and Inclusion: The data enables analysis of representation—by age, gender, and region—providing transparency into progress toward the Olympic spirit of global inclusivity. Users can pinpoint whether athlete diversity has increased and which countries or sports are at the forefront of this movement.
- Custom Interactivity and Self-Service Analytics: The dashboard features multiple layers of interactivity, including slicers for year, nation, sport, gender, and medal type. This enables users—regardless of technical background—to explore their own questions, from medal trends by continent to breakthrough performances by underdog countries.

## Final Conclusion
- This HR Analytics Dashboard project was designed to help organizations understand employee attrition trends through data-driven insights. Using Power BI, we analyzed key HR metrics such as Attrition Rate, Department-wise Attrition, Job Role Impact, and Demographic Influence on attrition.
- The dashboard simplifies complex HR data into clear and actionable visuals, empowering decision-makers to identify areas of concern and develop strategies to improve employee retention. The ability to slice data across Age, Department, and Job Role makes it a dynamic tool for in-depth HR analysis.
- This project not only demonstrates strong skills in Power BI and data storytelling, but also showcases the ability to translate raw data into business insights, which is essential for any data analytics role.
- This Olympics 2024 Power BI Dashboard transforms the immense complexity of the world’s largest sporting event into an accessible, interactive, and insight-rich experience. By merging historical context, real-time results, and multidimensional analysis, it provides not just a static recount of the Paris Games but a true exploration platform for understanding the dynamics of global athletic achievement.
- The project exemplifies how modern data analytics can move beyond simple reporting to generate strategic insights:
• Stakeholders can pinpoint investment opportunities in sports where their nations show rising potential.
• Sports governing bodies and analysts can explore deeper factors behind performance, such as age, gender, or the impact of program changes.
• The dashboard fosters both big-picture overviews and granular exploration, supporting broadcasting, policy, research, and fan engagement.
- Robust data modeling and the integration of advanced DAX measures ensure accuracy in all KPIs, while the model’s relationships enable true cross-filtering and multi-dimensional storytelling. The use of Power BI’s latest visual features—including custom tooltips, interactive maps, and dynamic filtering—creates a seamless analytics journey that engages both seasoned data professionals and casual sports fans.
- In sum, this dashboard not only showcases technical prowess in Power BI, DAX, and data modeling, but also underlines a commitment to democratizing Olympic data. It invites users to discover the stories behind the numbers, track historical legacies, and anticipate future trends for Olympic competition. As the Olympics continue to evolve, so too does the potential for data analytics to inspire, inform, and connect audiences around the globe.

## If you'd like to connect or collaborate on data projects, feel free to reach out on: 
• **LinkedIn**: www.linkedin.com/in/aditya-kumar-2852c
• **Email**: adityaakumaarr@gmail.com

