# Iram_HR-analytics-Dashboard-
Interactive HR dashboard built in Excel to analyze employee attrition across 1,470 employees. Uses pivot tables, charts and slicers to show who leaves by department, age, job role and overtime. Key finding: overall attrition is 16.1%, rising to 30.5% for employees working overtime. 
# HR Dashboard: Employee Attrition Analysis

![Dashboard Preview](dashboard.png)

## About the Project
- An interactive HR dashboard built in Microsoft Excel
- Analyzes employee attrition (employees leaving the company)
- Shows who is leaving, from which groups, and which factors are linked to it
- Helps HR teams plan better retention strategies

## Objectives
- Show total employees, current employees and ex-employees
- Find departments, job roles and age groups with the highest attrition
- Study the effect of overtime, income, marital status and business travel
- Give simple suggestions to reduce attrition

## Dataset
- 1,470 employee records
- 44 columns
- Main fields:
  - Attrition, Department, Job Role
  - Age Group, Gender, Marital Status, Education Field
  - Overtime, Business Travel, Distance From Home
  - Monthly Income, Job Satisfaction, Work-Life Balance
  - Years at Company, Years Since Last Promotion

## Tools Used
- Microsoft Excel
- Pivot tables
- Pivot charts
- Slicers
- Formulas and helper columns

## Data Preparation
- Checked for duplicate employees (none found)
- Created helper columns: age band, attrition label, attrition count, attrition rate
- Age bands: Under 25, 25-34, 35-44, 45-54, Over 55
- Ignored columns with the same value in every row (Over18, Standard Hours, Employee Count)
- Built pivot tables and linked them to charts and slicers

## Dashboard Features
- Key numbers: total employees, current employees, ex-employees, attrition rate
- Charts by department, age group and education field
- Slicers to filter data
- Everything on one dashboard sheet

## Key Insights
- Overall attrition rate is 16.1% (237 of 1,470 employees)
- Sales has the highest attrition among large departments (20.6%)
- R&D has the lowest attrition (13.8%)
- Employees under 25 leave the most (39.2%)
- Sales Representatives have the highest attrition by role (39.8%)
- Overtime: 30.5% attrition with overtime vs 10.4% without
- Single employees leave more (25.5%) than married (12.5%)
- Frequent travelers: 24.9% attrition vs 8.0% for non-travelers
- Average monthly income: 4,787 (left) vs 6,833 (stayed)

## Recommendations
- Reduce regular overtime
- Review pay for junior roles
- Support young employees with mentoring and career growth
- Review workload and targets for Sales Representatives
- Limit frequent travel where possible
- Take exit interviews to learn why people leave

## Repository Files
- `HR_Dashboard.xlsx`: dataset, pivot tables and dashboard
- `HR_Dashboard_Report.docx`: full project report
- `dashboard.png`: dashboard screenshot
- `README.md`: project description

## How to Use
- Download `HR_Dashboard.xlsx`
- Open it in Microsoft Excel
- Go to the dashboard sheet
- Use the slicers to filter and watch the charts update

## What I Learned
- Cleaning data in Excel
- Building pivot tables and pivot charts
- Designing a dashboard with slicers
- Explaining data insights in simple language

## Future Improvements
- Add more filters (job level, years since last promotion)
- Track attrition month by month
- Build the same dashboard in Power BI

## Author
- Iram
- [LinkedIn](https://www.linkedin.com/in/iram-shaikh-04b472443)
