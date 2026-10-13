# HR Analytics Dashboard | Power BI

## Project Overview

The **HR Analytics Dashboard** is an interactive Power BI project designed to analyze workforce trends and employee-related metrics. It helps explore employee attrition, engagement, compensation, promotion, retrenchment, and employee risk through dynamic KPIs and visualizations.

The project uses Power Query for data preparation, DAX for calculations, and Power BI features for interactive analysis and employee-level investigation.

## Objectives

- Analyze workforce distribution and employee demographics.
- Understand employee attrition and retention patterns.
- Evaluate employee engagement and satisfaction.
- Analyze compensation across departments, roles, and employee groups.
- Examine promotion and retrenchment indicators.
- Identify employees with higher scores across defined risk indicators.
- Enable interactive exploration through slicers, dynamic visuals, and drill-through.

## Tools and Technologies

- **Power BI Desktop** — Dashboard development and data visualization
- **Power Query** — Data cleaning, transformation, and merging
- **DAX** — Measures, calculated columns, KPIs, and risk calculations
- **Data Modeling** — Preparing the analytical HR dataset
- **Field Parameters** — Dynamic selection of metrics and dimensions
- **Bookmarks and Selection Pane** — Interactive dashboard display and navigation
- **Drill-through** — Employee-level investigation

## Dashboard Pages

### 1. Workforce Overview
- Total employees
- Attrition and retention rates
- Promotion and retrenchment indicators
- High-risk employee count
- Dynamic workforce metrics and HR rates

### 2. Attrition Analysis
- Attrition rate analysis across employee groups
- Department and job role comparisons
- Analysis by age band, job level, overtime, business travel, and tenure
- Interactive filtering to explore attrition patterns

### 3. Employee Engagement
- Job satisfaction
- Environment satisfaction
- Relationship satisfaction
- Work-life balance
- Performance rating
- Dynamic analysis by department, job role, job level, and other employee dimensions

### 4. Compensation Analysis
- Average and median monthly income
- Compensation analysis across departments and job roles
- Salary and tenure bands
- Monthly income versus years at company

### 5. Promotion and Retrenchment
- Employees due for promotion
- Promotion rate
- Retrenchment count and rate
- Promotion–retrenchment conflict indicator
- Dynamic analysis across employee groups

### 6. HR Risk Analysis
- Employee risk score and risk category
- High-risk employee metrics
- Risk category distribution
- Employee investigation table with risk and status indicators

### Employee Detail — Drill-through
An additional employee-level drill-through page displays selected employee information, including department, job role, job level, risk category, risk score, promotion status, retrenchment status, satisfaction, income, and tenure.

## Data Preparation

Power Query was used to:
- Split combined source columns and promote headers.
- Merge supporting employee, promotion, and retrenchment data into the main HR table.
- Create promotion, retrenchment, attrition, and conflict flags.
- Create age, salary, tenure, and distance bands.
- Calculate an employee risk score and assign risk categories.

The final analytical table contains employee-level information for dashboard analysis.

## Key DAX Measures

The project includes measures for:
- Total Employees
- Attrition Employees and Attrition Rate
- Retention Employees and Retention Rate
- Promotion Due and Promotion Rate
- Retrenchment Employees and Retrenchment Rate
- Promotion–Retrenchment Conflict Count
- Average and Median Monthly Income
- Employee Satisfaction Metrics
- Overtime Employees and Overtime Percentage
- High Risk Employees and High Risk Percentage
- Average Tenure and Average Years Since Promotion

## Employee Risk Scoring

The risk score is based on five defined indicators:

1. Overtime
2. Low job satisfaction
3. Low environment satisfaction
4. Low work-life balance
5. Frequent business travel

Each indicator contributes one point when its defined condition is met.

| Risk Score | Risk Category |
|---|---|
| 0–1 | Low |
| 2 | Medium |
| 3–4 | High |
| 5 | Critical |

This is a project-defined analytical indicator, not a validated prediction of employee behavior or actual attrition.

## Interactive Features

- Dynamic metrics and dimensions using field parameters
- Slicers for filtering employee groups
- Interactive charts and KPI cards
- Bookmarks for showing and hiding dashboard sections
- Conditional formatting for selected KPIs and employee risk indicators
- Employee-level drill-through analysis

## Project Screenshots

Dashboard screenshots are available in the `screenshots/` folder.

- Workforce Overview
- Attrition Analysis
- Employee Engagement
- Compensation Analysis
- Promotion and Retrenchment
- HR Risk Analysis
- Employee Detail

## How to Use

1. Download or clone this repository.
2. Open the Power BI report in `report/HR_Analytics_Dashboard.pbix`.
3. If Power BI requests a data source, configure the source path or connection for your environment.
4. Refresh the data if the source files are available.
5. Explore the dashboard pages using the slicers, dynamic selectors, and drill-through functionality.

The report may require the original source data to refresh successfully. Source data is not included unless explicitly provided in this repository.

## Key Learnings

- Data cleaning and transformation using Power Query
- Building an analytical data model in Power BI
- Creating DAX measures and calculated columns
- Developing interactive dashboards with field parameters
- Designing KPI-driven reports for HR analysis
- Implementing bookmarks, conditional formatting, and drill-through
- Translating employee-level data into structured analytical views

## Author

**Ganesh Sattu**

Aspiring Data Analyst | SQL | Power BI | DAX | Excel

- GitHub: https://github.com/codeganesh452
- Portfolio: https://codeganesh452.github.io/data-analyst-portfolio/

