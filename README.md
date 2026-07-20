# HR Analytics Dashboard – Power BI

**Overview**
An interactive Power BI dashboard analyzing employee attrition across 
departments, age groups, education fields, and job roles to help HR 
identify where and why employees are leaving.

**Business Question**
Which departments, age groups, and employee segments have the highest 
attrition, and what patterns can help HR reduce turnover?

**Tools Used**
Power BI (Power Query, Data Modeling, DAX)

**Process**
- Cleaned and modeled the HR dataset (1,470 employee records)
- Built KPI cards for Overall Employees, Attrition, Attrition Rate, Active Employees, and Average Age
- Created DAX measures for Attrition Rate (%), Attrition Count by segment, and Age Group breakdowns
- Added filters for Education Level (Associate's, Bachelor's, Doctoral, High School, Master's)
- Built visuals: Department-wise attrition (pie), Attrition by age group and gender (bar), Job Role attrition matrix (table), Education field attrition (bar), and Age-band attrition donuts (Under 25 to Above 55)

**Dashboard Preview**
![HR Analytics Dashboard](<img width="1866" height="742" alt="HR_analystic_DashBoard" src="https://github.com/user-attachments/assets/79f1d215-dee2-4546-904e-4a8ac572393d" />
)

**Key Insights**
- Out of **1,470 total employees**, **237 have left**, putting overall **attrition rate at 16.12%**
- **Sales department accounts for 65.37% of all attrition**, far outweighing R&D (30.34%) and HR (4.29%) — attrition is heavily concentrated in one department, not spread evenly across the business
- **Under-25 employees have the highest attrition rate at 47.37%**, more than double the rate of 35-44 year-olds (27.45%) and roughly 4x that of the 45-54 group — younger employees are leaving at a dramatically higher rate, likely an early-career retention issue
- Among job roles, **Sales Executive (326) and Laboratory Technician (259)** have the highest total attrition counts — worth checking if this is workload, compensation, or role-specific
- **Life Sciences (89) and Medical (63)** education fields show the most attrition by count — though this likely also reflects that more employees come from these fields overall, so attrition *rate* per field would be worth checking next
- The **25-34 age group has the largest workforce (554 employees)**, meaning even a moderate attrition rate here has an outsized impact on total headcount loss

**What I'd Improve / Next Steps**
- Add attrition **rate** (not just count) per Education Field and Job Role, since raw counts can be misleading when group sizes differ
- Investigate root causes for the Sales department and Under-25 group specifically (e.g., salary bands, tenure, overtime — if available in the dataset)
- Add a Monthly Income vs. Attrition view, since compensation often correlates strongly with turnover

**Files**
- `HR_Analytics_Dashboard.pbix`
- `<img width="1866" height="742" alt="HR_analystic_DashBoard" src="https://github.com/user-attachments/assets/7d17b5f0-3a7c-40dc-a29a-a8542c7436c3" />
`
