# TalentCore-Workforce-Analytics-Project
 TalentCore is a fictional pan-African technology services company with offices in Nairobi, Mombasa, Kisumu, Kampala, Dar es Salaam, and Kigali.With a workforce spread across six departments, TalentCore is committed to building a high-performing, engaged, and well-retained team through data-driven people decisions.
# TalentCore HR Analytics Dashboard

An interactive Power BI dashboard analyzing workforce demographics, employee performance, compensation, and attrition to support data-driven human resource decisions.

## Business Problem

TalentCore wants to understand its workforce composition, monitor employee retention, identify factors contributing to employee turnover, and evaluate departmental performance.

The analysis aims to answer:
- What is the organization's current workforce size?
- Which departments experience the highest employee attrition?
- What factors influence employee turnover and retention?
- How do salaries and employee performance vary across departments?
- What workforce trends can support better HR decision-making?

## Data

- **Source:** TalentCore HR dataset.
- **Dataset:** Employee-level HR records.
- **Contents:** Employee IDs, demographics, departments, job roles, hire dates, exit dates, employment status, salaries, performance ratings, training hours, and tenure.

## Approach

The project followed these steps:

1. **Data Cleaning:** Handled missing values, duplicate employee IDs, inconsistent formats, invalid ages, negative salary values, and inconsistent department names using Power Query.
2. **Data Transformation:** Standardized employment status, date fields, salary values, and other workforce attributes while preserving original exit date information.
3. **Data Modeling:** Created dimension tables for departments, job roles, and dates, and established relationships with the main employee table.
4. **DAX Measures:** Developed measures for total employees, active headcount, leavers, attrition rate, retention rate, average salary, tenure, and workforce movements.
5. **Data Visualization:** Developed interactive Power BI report pages covering workforce overview, departmental performance, attrition analysis, compensation and diversity, and executive summary.

## Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Microsoft Excel
- GitHub


## Project Status

Completed – TalentCore HR Analytics and Interactive Dashboard.


