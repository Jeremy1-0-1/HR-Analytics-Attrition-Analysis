HR Analytics: Workforce Attrition & Retention Analysis

📌 Project Overview

This project analyzes workforce attrition, retention patterns, and key drivers of employee exits using HR data. The objective is to provide executive-ready insights that support strategic workforce planning, retention initiatives, and risk identification across departments, job levels, tenure bands, and locations.

The analysis focuses on who is leaving, why they are leaving, and when exits are most likely to occur, presented through clean, decision-oriented Power BI dashboards.


HR-Analytics-Attrition-Analysis/
│
├── Dataset/                      → Original HR dataset used for analysis
├── Dashboard Screenshots/        → Final Power BI dashboard outputs
├── Power BI File/                → Complete interactive dashboard file (.pbix)
└── README.md                     → Project documentation


⸻

🎯 Business Objectives
	•	Understand overall workforce composition and attrition health
	•	Identify departments and roles with elevated attrition risk
	•	Examine whether performance, salary, or location influence exits
	•	Analyze tenure patterns to uncover critical retention risk periods
	•	Deliver executive-level dashboards that support data-driven HR decisions

⸻

🛠 Tools Used
	•	Microsoft Excel – Data cleaning, validation, helper columns, and quality checks
	•	Power BI – Data modeling, DAX calculations, dashboard design, and insights
	•	DAX – Measures for headcount, attrition rate, salary averages, and tenure analysis

⸻

❓ Why SQL Was Not Used in This Project

SQL was intentionally not used in this analysis because:
	•	The dataset was already well-structured and analysis-ready
	•	The project involved a single HR dataset, with no need for joins across multiple tables
	•	All required aggregations, segmentation, and calculations were efficiently handled using Power BI and DAX

SQL would not have added additional analytical value in this case. However, SQL would be appropriate if the data originated from multiple HR systems, required historical snapshots, or involved complex relational queries.

⸻

🧹 Data Preparation & Cleaning

Key preparation steps included:
	•	Interpreting attrition status (0 = Active, 1 = Exited)
	•	Treating blank exit dates as active employees
	•	Identifying and flagging missing or unreliable tenure values
	•	Creating helper flags for:
	•	Tenure reliability
	•	Date inconsistencies (exit date earlier than hire date)
	•	Retaining flagged records for overall attrition analysis while excluding them from tenure-based calculations

These decisions ensure analytical accuracy without discarding valuable workforce information.

⸻

📊 Dashboards Overview

📍 Dashboard 1: Workforce Overview & Attrition Snapshot

Goal: Provide an executive-level snapshot of workforce health and attrition.

Key Insights Delivered:
	•	Overall employee count, active employees, exited employees, and attrition rate
	•	Departments contributing most to employee exits
	•	Attrition distribution across job levels
	•	Breakdown of voluntary vs involuntary exits

Key Visuals & Purpose:
	•	KPI Cards: Instant workforce health indicators
	•	Attrition by Department (Bar Chart): Identify high-impact departments
	•	Workforce Composition by Job Level (100% Stacked Column): Compare exit proportions across levels
	•	Exit Type Breakdown (Donut): Understand nature of exits
	•	Insight Text Box: Executive summary interpretation

⸻

📍 Dashboard 2: Attrition Drivers & Workforce Risk Analysis

Goal: Identify key factors associated with employee exits.

Key Insights Delivered:
	•	Departmental attrition risk ranking
	•	Relationship between performance ratings and attrition
	•	Salary comparison between active and exited employees
	•	Geographic concentration of employee exits

Key Visuals & Purpose:
	•	Attrition Rate by Department (Ranked Bar): Highlight risk hotspots
	•	Attrition Rate vs Performance Rating (Column Chart): Assess performance impact
	•	Geographic Attrition Map: Identify regional exit patterns
	•	Salary Distribution by Attrition Status: Evaluate compensation influence
	•	Insight Text Box: Driver-based interpretation

⸻

📍 Dashboard 3: Employee Tenure & Retention Patterns

Goal: Analyze retention stability and identify critical exit periods.

Key Insights Delivered:
	•	Tenure distribution across the workforce
	•	Exit concentration by tenure band
	•	Retention strength across job levels

Key Visuals & Purpose:
	•	Tenure Distribution (Area Chart): Workforce lifecycle overview
	•	Exit Concentration by Tenure Band (Stacked Column): Identify risk windows
	•	Average Tenure by Job Level (Line/Dot Plot): Seniority-retention relationship
	•	Insight Text Box: Retention-focused recommendations

⸻

📈 Key Takeaways
	•	Attrition is concentrated in specific departments and early-to-mid tenure bands
	•	Performance ratings show minimal influence on attrition outcomes
	•	Salary differences between active and exited employees are marginal
	•	Higher job levels demonstrate stronger retention stability
	•	Early-career engagement and development initiatives present the greatest retention opportunity

⸻

📂 Repository Contents
	•	Power BI dashboard file (.pbix)
	•	Cleaned dataset
  • Dashboard Images with insight boxes
 • README documentation

⸻

🔗 Author

A. Jeremiah Martins
Junior Data Analyst | Power BI | Excel | SQL | Data Storytelling
