# Healthcare Operations & Patient Analytics Dashboard

This repository contains a comprehensive Power BI project designed to analyze healthcare facility operations, patient demographics, and clinical outcomes. The dashboard transforms raw hospital data into actionable intelligence, enabling healthcare administrators to optimize resource allocation, monitor patient satisfaction, and track critical care metrics.

## Project Overview
This project provides a multi-faceted view of hospital performance across different departments and timeframes. It features interactive filtering by Department_Name and MonthName to allow for granular analysis of operational bottlenecks and patient flow.   

1. Hospital Summary (Operations & Revenue)
The Hospital Summary view focuses on high-level facility metrics, staff resource management, and patient feedback.

- Key Performance Indicators (KPIs): Tracks 2.506K Total Patients, 1.679K In Patients, 827 Out Patients, and 262 Total Staff.
- Financial & Resource Metrics: Monitors Average Treatment Cost (161.41) and Patient to Staff Ratio (0.10) alongside an Occupied Bed gauge showing 1751 current beds in use.   
- Departmental Efficiency: Highlights the Average ER Time by Department, identifying the Outpatient Department (OPD) as having the highest average ER wait time at 96 minutes.   
- Revenue & Satisfaction: Correlates Total Revenue by Age Group (peaking in the 6-20Y demographic at 0.14M) with patient feedback ratings, which show an overall positive trend in the 6-20Y bucket.  
- Trend Analysis: Displays weekly patient inflow trends comparing In Patient vs. Out Patient volumes from Week 31 to Week 35.

2. Patient Summary (Clinical Outcomes & Demographics)
The Patient Summary view shifts the focus toward clinical care outcomes, length of stay (LOS), and patient profiling.

- Clinical KPIs: Tracks Total Discharges (209), Average Length of Stay (1.70 days), ICU admissions (82), and Mortality/Death (86) against Total Revenue (404.49K).
- Department Status: Features a detailed stacked bar chart analyzing In Patients by Department and Status (categorized into Death, Discharge, ICU, Normal, and Readmit), with Physical Medicine and Rehabilitation showing significant activity.
- Demographic Breakdown: Visualizes the patient base by gender (51.08% Male, 48.92% Female) and age buckets, revealing the 6-20Y and 41-60Y groups as the highest volume demographics.
- Length of Stay Analysis: A dedicated area chart tracks the Average LOS by Age Group, indicating that older demographics (60+Y and Below 6Y) experience the longest average hospitalization periods (up to 2.00 days).  
- LOS Distribution: A funnel chart breaks down Total Patients by LOS, showing the vast majority stay between 1 to 2 days.

## Technical Stack & Skills Demonstrated
- Business Intelligence: Power BI (Data Modeling, DAX, Interactive Visualizations)
- Data Engineering: Extraction, Transformation, and Loading (ETL) of complex healthcare datasets to ensure accurate KPI calculations.
- Analytics Focus: Time-Series Analysis (Weekly patient flow), Demographic Profiling, and Operational Benchmarking.
