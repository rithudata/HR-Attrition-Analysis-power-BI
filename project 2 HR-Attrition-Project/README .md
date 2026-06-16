# 🧑‍💼 HR Attrition Analysis — MySQL & Power BI

## Project Overview
This project analyzes employee attrition data to identify key factors 
influencing employee turnover. The goal is to understand why employees 
leave and help organizations take action to reduce attrition.

**Dataset:** IBM HR Analytics Dataset (Kaggle) — 1,470 employee records  
**Database:** hr_project (MySQL)

## Tools Used
- **MySQL Workbench** — data import, cleaning, exploration, SQL analysis
- **Power BI** — interactive dashboard and visualizations

## Problem Statement
Employee attrition is a major challenge for organizations. This project aims to find:
- Which factors increase attrition risk
- Which employee groups are most at risk
- What business actions can reduce turnover

## Key KPIs
| Metric | Value |
|--------|-------|
| Total Employees | 1,470 |
| Employees Who Left | 237 |
| Employees Retained | 1,233 |
| Overall Attrition Rate | **16.1%** |
| Age Range | 18 – 60 years |
| Average Age | ~36.9 years |
| Monthly Income Range | $1,009 – $19,999 |

## Department Distribution
| Department | Employees |
|------------|-----------|
| Research & Development | 961 |
| Sales | 446 |
| Human Resources | 63 |

## Key Findings & Insights

### 🔴 Overtime is the Strongest Attrition Driver
Employees working overtime show **30%+ higher attrition** compared to others.

### 💰 Low Income = Higher Attrition
Employees earning $1,000–$5,000/month form the largest group —
and show the highest attrition rate. Higher income groups are more stable.

### ✈️ Business Travel Risk
Employees who travel frequently show higher attrition risk.
Travel_Rarely group (1,043 employees) is the most stable.

### ⚖️ Work-Life Balance
Poor work-life balance is strongly linked to employees leaving the organization.

### 👤 Personal Factors
Single employees and early-career employees show higher attrition patterns.

## Final Conclusion — Top Attrition Drivers
1. **Overtime** (strongest factor)
2. **Low monthly income**
3. **Low job involvement**
4. **Poor work-life balance**
5. **Single marital status**
6. **Early career stage**

## Data Cleaning Performed
- Verified no duplicate Employee Numbers
- Confirmed no NULL values in key fields
- Validated categorical values
- Logical checks: YearsInCurrentRole ≤ YearsAtCompany

## Files Included
- SQL analysis scripts
- Power BI dashboard (.pbix)
- Dashboard screenshot

## About Me
Aspiring Data Analyst from Tamil Nadu, India.  
Skills: SQL, Power BI, MySQL, Data Cleaning, Business Insight Generation.  
Open to freelance data projects and entry-level analyst opportunities.



