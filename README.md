# Project-Management-Analytics-Dashboard
Project Management Analytics Dashboard. Built using Microsoft Excel analysing 4,000 projects worth $4.57 Billion.

> Transforming raw project data into clear, 
> actionable insights using Microsoft Excel.

---

##  About Me

**Shivani Siddula**  
Aspiring Data Analyst

Data enthusiast focused on improving project 
efficiency through KPI tracking and risk analysis. 
Skilled in transforming complex datasets into 
clear, actionable dashboards. Detail-oriented 
with a strong interest in data analytics.

📧 Email: shivanisiddula01@gmail.com  
🔗 LinkedIn: linkedin.com/in/shivanisiddula

---

##  Project Overview

This **Project Management Analytics Dashboard** 
was built using **Microsoft Excel** to analyse 
**4,000 projects** across **6 project types** 
with a total portfolio value of **$4.57 Billion**.

The dashboard helps project managers and 
stakeholders monitor budget utilization, risk 
exposure, resource allocation and project 
progress — all in one interactive view.

---

##  Dataset Details

| Metric | Value |
|--------|-------|
| Total Projects | 4,000 |
| Total Budget | $4,572,126,011 |
| Total Stakeholders | 44,522 |
| Total Resources | 2,606.78 |
| Avg Budget Utilization | 94.57% |
| Avg Project Timeline | 17.15 Months |
| Total Fields | 50+ Columns |
| Project Types | 6 Categories |

###  Project Types Analysed

| Project Type | Projects | Budget | Key Characteristic |
|--------------|----------|--------|--------------------|
| Construction | 797 | $1,394,032,918 | Highest budget |
| IT | 1,381 | $1,232,728,129 | Highest resources |
| R&D | 588 | $1,024,810,146 | High budget moderate risk |
| Marketing | 418 | $324,732,587 | Low budget high risk |
| Manufacturing | 418 | $299,308,400 | Fastest delivery |
| Healthcare | 398 | $296,513,832 | Safest type |

---

##  Dashboard Structure

The dashboard is organised into
6 professional sheets:

### Sheet 1 — Project Data
Rows   → Project Type
Values → Sum of Stakeholder Count
Chart  → Pie Chart
Slicer → Project Type
Analyses stakeholder distribution
across all 6 project types.
Total stakeholders tracked = 44,522

---

### Sheet 2 — Risk & Estimation
Rows   → Project Type → Risk Level
Values → Sum of Budget (USD)
Sum of Resource Availability
Count of Risk Level
Chart  → Combo Chart (Column + Line)
Slicers→ Project Type + Risk Level
Analyses budget allocation and
risk exposure per project type.
Total budget monitored = $4,572,126,011

---

### Sheet 3 — Project Status
Rows   → Project Type → Project Phase
Values → Count of Project Phase
Avg Budget Utilization Rate
Avg Estimated Timeline Months
Count of Priority Level
Chart  → Stacked Bar Chart
Slicers→ Project Type +
Project Phase +
Priority Level
Tracks project phase progress,
budget utilization and timeline
per project type.

---

### Sheet 4 — Project KPIs

| KPI | Value | Formula |
|-----|-------|---------|
| Total Projects | 4,000 | =COUNTA(Project_ID)-1 |
| Total Budget | $4.57B | =SUM(Project_Budget_USD) |
| Total Stakeholders | 44,522 | =SUM(Stakeholder_Count) |
| Critical Risk | 962 | =COUNTIF(Risk_Level,"Critical") |
| High Risk | 1,036 | =COUNTIF(Risk_Level,"High") |
| Avg Utilization | 94.57% | =AVERAGE(Budget_Utilization_Rate) |

---

### Sheet 5 — Project Key Insights
5 critical findings displayed in
a tree structure layout with
color coded severity indicators.

---

### Sheet 6 — About Me
Personal profile and project
summary section.

---

## Key Findings

| # | Severity | Insight |
|---|----------|---------|
| 1 | 🔴 Critical | Avg Budget Utilization 94.57% — portfolio critically close to overspending |
| 2 | 🔴 Critical | 49.95% of 4,000 projects are High or Critical risk — urgent attention needed |
| 3 | 🟠 Warning | Construction + IT consume 57.5% of total $4.57B budget |
| 4 | 🟠 Warning | IT dominates all metrics — stakeholders (13,101) resources (896) risk (1,381) |
| 5 | 🟢 Positive | Healthcare is safest — lowest budget ($296M) risk (398) and timeline (12.85 months) |

---

##  Problems Identified

| # | Problem | Impact |
|---|---------|--------|
| 1 | 94.57% avg utilization | Budget overrun risk |
| 2 | 49.95% High or Critical risk | Portfolio stability at risk |
| 3 | Construction + IT = 57.5% budget | Over concentration |
| 4 | IT overloaded on all metrics | Resource burnout risk |
| 5 | Construction 23.26 month timeline | Delay and cost risk |
| 6 | R&D $366M critical exposure | Financial danger |
| 7 | Healthcare underfunded | Capacity risk |
| 8 | No low risk buffer (only 20.15%) | Portfolio fragility |

---

##  Tools & Skills Used
✅ Microsoft Excel
✅ Pivot Tables & Charts
✅ Slicers & Interactive Filters
✅ KPI Card Design
✅ Dashboard Layout & Design
✅ Data Analysis & Visualization
✅ Data Cleaning & Transformation
✅ Business Problem Identification
✅ Documentation & Reporting
