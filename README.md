<img width="616" height="341" alt="snap of Dashboard" src="https://github.com/user-attachments/assets/710ab256-7a4e-4287-bf4d-b81afd4cecf8" />

HR Analytics Dashboard (Power BI)-
Built an interactive HR Analytics Dashboard in Power BI to analyze and visualize employee data and attrition trends. 

✅ Key Features: 
- Overall KPIs: Employee Count, Active Employees, Attrition Count, Attrition Rate, and Avg. Age 
- Visuals: Department-wise attrition, Education-wise attrition, Age-group distributions, Gender-based attrition, and Job Satisfaction Ratings 

🧮 Calculated Fields Used: 
- Attrition Rate = (Attrition Count / Total Employees) * 100 
- Active Employees = [Employee Count] – [Attrition Count] 
- Age Groups = IF [Age] BETWEEN 18 AND 25 THEN "18–25" 
 ELSEIF [Age] BETWEEN 26 AND 35 THEN "26–35" 
 ELSEIF [Age] BETWEEN 36 AND 45 THEN "36–45" 
 ELSEIF [Age] BETWEEN 46 AND 55 THEN "46–55" 
 ELSE "56+" END 
- Gender-wise Attrition % = SUM([Attrition]) / SUM([Employees]) by Gender 

📊 Insights: 
- R&D and Sales departments show the highest attrition 
- Employees aged 26–35 are most affected 
- Bachelor’s degree holders have maximum attrition 
- Male employees show higher attrition compared to females 
- Roles like Sales Representative & Lab Technician have lower job satisfaction, leading to higher attrition.

Purpose:

• Improve employee retention strategies
• Enhance workforce planning
• Make data-driven decisions for better employee experience

⚙️ Tools Used: Power BI (Dashboarding & Visualization), Excel (Data Preparation & Cleaning)
Skills: Microsoft Power BI · Microsoft Power Query · Data Analysis · Microsoft Excel · Data Visualization

