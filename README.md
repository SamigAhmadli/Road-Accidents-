# Road Accident Dashboard (2021-2022)

## Description
This Excel project creates a dynamic dashboard to analyze road accident data for 2021 and 2022. It includes data cleaning, preprocessing, and visualization features such as pivot tables, charts, and interactive filters.

## Technologies Used
Excel: Used for data cleaning, preprocessing, analysis, and visualization.

## Problem Statement
We must analyze key indicators for road accident data to gain insights into road safety. Specifically, we want to calculate the following metrics:

- **Total Casualties**: The sum of all casualties in road accidents.
-**Accident Severity**: The distribution of accident severity levels (Fatal, Serious, Slight).
-**Casualties by Vehicle Type**: The number of casualties involving different vehicle types.
-**Monthly and Yearly Trends**: Trends in road accidents over months and years.

## Features
- **Data Cleaning**: Fix typos, filter data, and ensure consistency.
- **Data Preprocessing**: Add columns for month and year to analyze trends.
- **Data Visualization**: Create donut charts, bar charts, and tree maps for insights.
- **Interactive Dashboard**: Use slicers and timelines to filter data dynamically.

## Installation
1. Download the Excel file (`road_accident_dashboard.xlsx`) from this repository.
2. Open the file in **Microsoft Excel** (2016 or later).

## Usage
1. **Data Input**: Load your dataset into the `Data` sheet.
2. **Data Cleaning**: Use the `Find and Replace` tool to fix typos (e.g., "Fetal" to "Fatal").
3. **Data Analysis**: Explore the `KPIs` sheet for pivot tables and calculations.
4. **Dashboard**: Navigate to the `Dashboard` sheet to view visualizations and interact with filters.


## Data Cleaning Process
-**Identify and Filter Data**:
Select the first column of your dataset.
Go to the Home ribbon, click on Sort & Filter, and then select Filter.
Filter the data to identify any wrong or missing values.

-**Correct Typo Errors**:
Select the severity column, and press Ctrl + F to open the Find and Replace dialog box.
Replace "Fetal" with "Fatal".

-**Verify Corrections**:
Check the severity column to ensure all instances of "Fetal" has been corrected to "Fatal".

## Data Preprocessing
-**Add Month and Year Columns**:
Insert new columns for Month and Year.
Use the TEXT function to extract the month and year from the date.

## Data Analysis and Visualization
-**Create Pivot Tables**:
Insert pivot tables to calculate total casualties, accident severity, and other metrics.

-**Create Charts**:
Insert donut charts, bar charts, and tree maps to visualize the data.

## Visualization and Dashboard Building
-**Create Donut Charts for Severity Levels**:
Create and format donut charts for Fatal, Serious, and Slight severities.

-**Add KPI Titles and Values**:
Insert text boxes for KPI titles and link them to the corresponding values.

-**Add Donut Charts to the Dashboard**:
Copy the formatted donut charts to the dashboard sheet.

-**Add Percentage Values to Donut Charts**:
Insert and link text boxes for percentage values in the donut charts.

-**Create Additional KPIs**:
Create pivot tables and charts for vehicle types, road types, and other metrics.

## Final Touches
Please make sure all elements are properly aligned and formatted.
Test the dashboard to make sure all filters and interactivity work as expected.

## Road Accident Dashboard Insights
## Overview
Welcome to the Road Accident Dashboard! This dashboard provides an in-depth analysis of road accident data, helping us to track performance, understand accident patterns, and make data-driven decisions to improve road safety. Below, I've included detailed insights into each key metric and visualization displayed on our dashboards.


## Total Casualties Overview

## Description:
This screenshot shows the total number of casualties: 417,883, calculated using Pivot Tables in Excel.

![Screenshot 2025-02-16 085528](https://github.com/user-attachments/assets/9a314f2e-afa9-40b9-b7dd-4173f35eee33)

## Insights:
Highlights the scale of road accidents, emphasizing the need for safety measures.
Pivot Tables enabled efficient data aggregation and analysis.

## Fatal Casualties KPI

## Description
Fatal Casualties: 7,135 (1.7% of total casualties).

This KPI highlights the most severe road accidents, emphasizing the need for targeted safety measures.

![Screenshot 2025-02-16 085606](https://github.com/user-attachments/assets/2d291456-380b-477a-bf65-ee15b94d2aed)

## Calculation
Used a Pivot Table to sum casualties by severity.

Calculated the percentage of fatal casualties using:
=Fatal_Casualties / (Fatal_Casualties + Non_Fatal_Casualties).

Result: 1.7% of all casualties were fatal.

## Insights
Urgent Attention Needed: Fatal accidents, though a small percentage, are critical and require immediate intervention.

Targeted Actions: Focus on high-risk areas, improve road signage, and enforce speed limits to reduce fatalities.


