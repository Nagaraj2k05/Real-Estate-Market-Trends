👩‍💼 HR Analytics Dashboard (Power BI)

📊 Analyze Employee Performance, Satisfaction, and Turnover Metrics

This Power BI project helps HR professionals visualize and understand the workforce better — from performance reviews to turnover rates.

---

🎯 Objective

To build an interactive HR dashboard that tracks:
- Employee distribution by department & gender
- Satisfaction vs Performance correlation
- Turnover trends & recruitment analysis
- Salary & tenure insights

---

📁 Files Included

| File Name                 | Description                               |
|---------------------------|-------------------------------------------|
| `HR_Data_Cleaned.csv`     | Cleaned HR dataset used in the report     |
| `HR_Analytics.pbix`       | Final Power BI dashboard file             |
| `Screenshots/`            | Folder containing dashboard preview images|

---

📊 Dashboard Overview

🔹 Page 1: HR Summary  
> KPIs, Employee distribution, Gender breakdown

🔸 Page 2: Performance & Satisfaction  
> Bar charts, Scatter plots, Score trends

🔹 Page 3: Turnover & Hiring  
> Monthly hiring, Turnover matrix, Line graphs

🔸 Page 4: Salary & Tenure  
> Avg salary by dept, tenure insights

---

⚙️ Tools Used

- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query for Data Cleaning  
- Microsoft Excel for raw data prep

---

🧠 DAX Measures Used

```DAX
Total Employees = COUNT(HR_Data[EmployeeID])
Avg Satisfaction = AVERAGE(HR_Data[SatisfactionScore])
Turnover Rate (%) = DIVIDE([Total Terminated], [Total Employees]) * 100
