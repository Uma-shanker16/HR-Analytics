# HR Analytics Dashboard (Tableau)

## Project Background

This project focuses on building an interactive HR analytics dashboard to help HR leaders monitor workforce trends, employee attrition, and demographic patterns using Tableau. The dashboard enables data-driven decision-making around hiring, retention strategies, and workforce planning.

Insights and recommendations are provided on the following key areas:

- **Workforce Overview**
- **Attrition Trends**
- **Employee Demographics**
- **Job Satisfaction & Engagement**

An interactive Tableau dashboard used to explore workforce trends can be found here:[ \[Tableau Dashboard Link\]](https://public.tableau.com/app/profile/uma.shanker.chintha/viz/Book1_17544275136860/HRANALYSTICSDASHBOARD)

---

## Data Structure & Initial Checks

The dataset used for this analysis was sourced from an Excel file containing approximately **1,470 employee records** and **39 attributes** covering demographics, employment history, and satisfaction metrics.

Key fields included:
- Employee ID
- Age
- Gender
- Department
- Job Role
- Education
- Attrition Status
- Job Satisfaction
- Hiring & Exit Information

Initial steps included:
- Reviewing dataset granularity and structure
- Identifying missing values and inconsistencies
- Creating calculated fields for attrition metrics
- Preparing data for visualization in Tableau

---

## Executive Summary

### Overview of Findings

The HR Analytics Dashboard highlights workforce composition, attrition patterns, and satisfaction trends across departments and demographics.  

Three key insights emerged:
1. Attrition rates vary significantly across job roles and age groups.
2. Certain departments show higher turnover, indicating potential engagement or workload issues.
3. Job satisfaction strongly correlates with retention, especially in early-career employees.

The dashboard enables HR leaders to monitor workforce health and take proactive action.

---

## Data Preparation and Analysis Strategy

Before building visuals, the data was thoroughly studied to understand structure, relationships, and flow.

### Data Source
- Excel dataset with ~1,470 rows and 39 columns.

### Calculated Fields
Custom calculations were created to derive actionable insights:

- **Attrition Count**

- **Attrition Rate**

- **Active Employees**

### Connection Types
- Live connection for real-time updates
- Extract connection for improved performance and offline analysis

---

## Key Performance Indicators (KPIs)

The dashboard includes a KPI summary section providing a quick overview:

- **Total Employees**
- **Attrition Count**
- **Attrition Rate (~16.12%)**
- **Active Employees**
- **Average Age**

These metrics help leadership quickly assess workforce health.

---

## Insights Deep Dive

### Workforce Overview

* **Employee headcount trends.** Total workforce distribution across departments and job roles.
* **Active workforce analysis.** Identification of departments with highest active employee counts.
* **Age distribution.** Workforce composition across different career stages.
* **Gender representation.** Overall diversity insights across the organization.

---

### Attrition Trends

* **Attrition by department.** Departments with highest turnover identified.
* **Attrition by gender.** Comparative analysis of male vs female attrition.
* **Attrition by age group.** Early-career employees show higher turnover patterns.
* **Attrition timeline.** Trend patterns across employment tenure.

---

### Demographics Analysis

* **Age group segmentation.** Using bins and parameters to dynamically analyze age ranges.
* **Education distribution.** Workforce composition by education level.
* **Role-based segmentation.** Attrition and retention patterns by job role.
* **Diversity insights.** Workforce balance across demographic categories.

---

### Job Satisfaction & Engagement

* **Heat map analysis.** Job satisfaction ratings across roles.
* **Correlation with attrition.** Low satisfaction linked to higher turnover.
* **Engagement hotspots.** Roles with highest engagement levels.
* **Retention indicators.** Satisfaction-driven retention patterns.

---

## Advanced Visualizations

### Lollipop Chart – Attrition by Gender
Dual-axis visualization combining bars and circles to clearly compare attrition across genders.

### Frequency Chart – Age Groups
Bins and parameter-driven analysis allowing dynamic adjustment of age intervals.

### Heat Map – Job Satisfaction
Color gradient visualization showing satisfaction ratings across job roles.

### Donut Charts – Attrition by Age & Gender
Layered pie charts using a dummy axis to display segmented attrition insights.

---

## Dashboard Design & Interactivity

### Custom Design
- Background created using gradient styling
- Tableau dashboard layout aligned for executive reporting

### Interactivity Features
- Global filters for education, department, and gender
- Action filters to dynamically update all charts
- Click-based exploration for department-level insights

---

## Recommendations

Based on the insights, HR leadership should consider:

* Strengthening retention programs in high-attrition departments.
* Improving onboarding and engagement for early-career employees.
* Conducting targeted satisfaction improvement initiatives.
* Monitoring diversity and inclusion metrics continuously.
* Leveraging predictive analytics for workforce planning.

---

## Assumptions and Caveats

During the analysis, several assumptions were made:

* Missing demographic values were excluded from calculations.
* Attrition defined strictly based on recorded exit status.
* Satisfaction scores assumed consistent across survey periods.
* Dataset reflects a snapshot, not a real-time HRIS feed.
