# Patient-Wait-List-
# Patient Waitlist Analysis Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/1168b2f9-a77f-4fa9-bd6a-51dc78aa97d9/ReportSection?experience=power-bi

## Problem Statement

The healthcare organization is managing a significant patient waitlist and requires insights to optimize patient flow, resource allocation, and case management. The aim is to analyze:

Waitlist distribution across age profiles, case types, and time bands.
Trends in case types (Outpatient, Day Case, Inpatient) over time.
Comparative metrics (average and median) for specific medical departments and their contribution to the waitlist.


### Steps followed 

Data Collection:

Gathered patient data, including wait times, case types, age profiles, and department-specific metrics.
Extracted historical records to analyze trends over different time periods.
Data Transformation:

Cleaned data to remove inconsistencies.
Aggregated data into key categories like Case_Type, Time_Bands, Age_Profile, and Archive_Date.
Dashboard Design:

Created visuals:

Card Visual: Displays the latest month’s total waitlist (112K).  
Stacked Bar Chart: Analyzes avg/median waitlist by age and time bands.  
Donut Chart: Shows the percentage distribution of avg/median waitlist by Case_Type. 
Line Graphs: Tracks the sum of total cases by Archive_Date and Case_Type.  
Added slicers for filtering by Archive_Date and Case_Type.  
Incorporated department-wise avg/median insights (right panel).

Analysis:

Segmented data by time bands to understand waitlist aging.
Assessed trends in outpatient, day case, and inpatient categories.
Computed summary statistics (average and median) for departments.
# Insights

Overall Waitlist:

112K patients are on the waitlist, highlighting significant pressure on resources.
Age and Time Bands:

A considerable portion of patients aged 16-64 and 65+ have longer wait times (18+ months).
Younger patients (0-15) tend to have shorter wait periods (0-3 months).
Case Type Distribution:

Outpatients account for the majority of the waitlist (73.45%), followed by Inpatients (17.5%) and Day Cases (8.97%).
Resource allocation could focus on outpatient services for maximum impact.
Trend Analysis:

There is a declining trend in Day Case and Inpatient categories over time.
Outpatient numbers show relatively stable patterns, indicating consistent demand.
Department-Level Metrics:

Departments like Accident & Emergency, Anaesthetics, and Cardiology have identical avg/median lists (106.94). This suggests a need for further granularity in department-specific metrics.
