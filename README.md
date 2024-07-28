
#  Patient wait time analysis

##### Dashboard Link : (Since I don’t have a Microsoft company/business account I’m unable to host the dashboard so attaching an offline file here in GitHub). 

## 📝Problem Statement

This project focuses on analysing the average patient wait time for a healthcare centre using publicly available healthcare data. The dataset includes two categories: inpatient and outpatient, covering the years 2018-2021.

## 📋Terminologies

- Day Case: Patient admitted for less than a day
- Inpatient: Patient admitted for more than a day
- Outpatient: Patient receiving medical treatment without being admitted to a hospital

## 🎯Overall Objectives
- Track the current status of the patient waiting list
- Analyse historical monthly trends of waiting lists in both  inpatient and outpatient categories
- Perform detailed specialty level and age profile analysis

## 📊Dashboards
- Summary Dashboard: Provides an overview and key insights
- Detailed Dashboard: Allows for granular analysis

## ⚡Metrics & Connections used
- Metrics: Average and median waiting list times, current total wait list.
- Data Connection: Used a folder data connector to aggregate multiple Excel files, which were then imported into Power BI.

## 🔎Data Transformation
- Verified and corrected column data types, ensured matching column headers between CSV files (inpatient and outpatient), and matched row counts with the base Excel data file.
- Appended tables using an append query and renamed it as Overall_Inplusout_patient.
- Mapped repetitive disease names in the Specialty_Name column to generic categories (e.g., Respiratory, Heart, Teeth, Brain) using Excel pivots and relationships with Overall_Inplusout_patient.

## 💡Interactivity Features & Insights
- Key Performance Indicators (KPIs): Latest month wait list and previous year’s latest month wait list.
- Visualisations: Line chart for month-on-month case type analysis (day case, inpatient), pie chart for case type percentage and average/median segregation, stacked column chart for age group bifurcation, and a multi-row card for specialty groups.
- Filters: The summary dashboard includes filters - date range, case type, specialty name, and measures, all linked to charts and other dashboards.
- Detailed Dashboard: Enables detailed granular analysis based on date range, case type, specialty group, age group, and time bands on a month-on-month basis.

## 📸Dashboard Snippets

#### Dashboard 1 - Overall Summary
![Summary dashboard - Screenshot 1](https://github.com/user-attachments/assets/1baf7ea2-7a47-41f2-8131-bdb91c8a14fd)

#### Dashboard 2 - Details
![Details dashboard - Screenshot 2](https://github.com/user-attachments/assets/2e36fdc3-2024-42da-807f-ce881095156d)

#### Table View
![Table view - Screenshot 3](https://github.com/user-attachments/assets/7665d2b9-25bd-4f17-9068-046f517a79b0)
