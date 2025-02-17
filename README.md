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

## Serious Casualties KPI
## Description
Serious Casualties: 59,312 (14.2% of total casualties).

This KPI highlights accidents with severe but non-fatal outcomes, indicating areas where preventive measures can reduce harm.

![Screenshot 2025-02-16 085639](https://github.com/user-attachments/assets/083bcc5a-db26-4c5e-96e9-18d638354811)

## Calculation
Used a Pivot Table to sum casualties by severity.

Calculated the percentage of serious casualties using:
=Serious_Casualties / (Serious_Casualties + Slight_Casualties + Fatal_Casualties).

Result: 14.2% of all casualties were serious.

## Insights
Preventive Measures Needed: Serious accidents represent a significant portion of casualties, emphasizing the need for interventions to reduce severity.

Focus Areas: Improve road infrastructure, enforce traffic laws, and promote safe driving practices to prevent serious injuries.

## Slight Casualties KPI
## Description
Slight Casualties: 351,436 (84.1% of total casualties).

This KPI represents the majority of road accidents, highlighting the need for general safety improvements.

![Screenshot 2025-02-16 085705](https://github.com/user-attachments/assets/616a94bb-f8f4-435b-b835-0400b70899b8)

## Calculation
Used a Pivot Table to sum casualties by severity.

Calculated the percentage of slight casualties using:
=Slight_Casualties / (Slight_Casualties + Serious_Casualties + Fatal_Casualties).

Result: 84.1% of all casualties were slight.

## Insights
General Safety Improvements Needed: Slight accidents make up the majority of casualties, emphasizing the need for broad safety measures.

Focus Areas: Enhance road maintenance, increase driver awareness, and implement traffic calming measures to reduce minor accidents.

## Casualties by Car
## Description
Casualties Involving Cars: 333,485 (79.8% of total casualties).

This KPI highlights the significant role of cars in road accidents, emphasizing the need for targeted safety measures for car users.

![Screenshot 2025-02-16 085735](https://github.com/user-attachments/assets/b7c5003a-e96e-4518-8baf-d3c8f8f35af6)

## Calculation
Used a Pivot Table to group casualties by vehicle type (e.g., cars, agricultural vehicles, buses, etc.).

Calculated the percentage of car-related casualties using the formula:
=Cars / (Cars + Others)

Here, Cars = 333,485, and Others = 84,398 (sum of casualties involving other vehicle types).

Result: 79.8% of all casualties involved cars.

## Insights
Focus on Car Safety: Cars are involved in the majority of accidents, indicating a need for improved safety features, driver training, and traffic regulations.

Targeted Interventions: Promote seatbelt usage, reduce distracted driving, and enforce speed limits to reduce car-related casualties.

Other Vehicle Types: Agricultural vehicles, buses, and other types account for 20.2% of casualties, highlighting the need for safety measures in these areas as well.

## CY Casualties vs PY Casualties Trend
## Description
This analysis compares the Current Year (CY) and Previous Year (PY) trends in road accident casualties over 12 months (January to December).

The goal is to identify seasonal patterns, year-over-year changes, and areas for improvement.

![Screenshot 2025-02-16 085813](https://github.com/user-attachments/assets/29c40183-c5f0-47ff-94ec-978e4f388634)

## How It Was Done
## Data Preparation:

Organized casualty data by month for both CY and PY.

Pivot Table Setup:

Created a Pivot Table to group casualties by month for CY and PY.

Used a Line Chart to visualize the trends for easy comparison.

## Insights:

Identified months with the highest casualties (e.g., peak months like holidays or winter).

Compare CY and PY trends to assess whether casualties are increasing or decreasing over time.

## Key Insights
Seasonal Patterns: Certain months (e.g., December, July) may show higher casualties due to factors like holidays or weather conditions.

Year-over-Year Comparison:

If CY casualties are higher than PY, it indicates a need for stronger safety measures.

If CY casualties are lower, it suggests that previous interventions may be effective.

Actionable Steps: Use the trend data to plan targeted safety campaigns during high-risk months.

## Casualties by Road Type
## Description
This analysis breaks down road accident casualties by road type, highlighting which types of roads are most dangerous.

The data includes:

Single Carriageway: 30.9K

Dual Carriageway: 67.4K

Roundabout: 26.8K

One Way Street: 7.4K

Slip Road: 4.7K

Other/Unspecified: 1.9K

![Screenshot 2025-02-16 085835](https://github.com/user-attachments/assets/0a8eedb4-86b7-42ee-b5a4-8e1465716378)

## How It Was Done

Pivot Table Setup:

Created a Pivot Table to group casualties by road type.

Visualized the data using a Bar Chart to compare casualties across different road types.

## Insights:

Identified which road types have the highest number of casualties.

Highlighted potential areas for infrastructure improvements or traffic regulation changes.

## Key Insights
Dual Carriageways: Account for the highest number of casualties (67.4K), suggesting a need for better traffic management and safety measures on these roads.

Single Carriageways: Also significant (30.9K), indicating the need for improved road design and signage.

Roundabouts: 26.8K casualties suggest that driver behavior and roundabout design may need review.

One-Way Streets & Slip Roads: Lower casualties but still important to address for overall road safety.

## Description
This analysis breaks down road accident casualties by road surface conditions, highlighting the impact of weather and road conditions on accidents.

The data includes:

Wet Roads: 115,261 casualties

Dry Roads: 279,445 casualties

Snow/Ice: 22,781 casualties

![Screenshot 2025-02-16 085901](https://github.com/user-attachments/assets/173b8111-1e30-4a2d-be04-117b97bd3174)

## How It Was Done
## Data Preparation:

Cleaned and categorized the dataset by road surface conditions (wet, dry, snow/ice).

Pivot Table Setup:

Created a Pivot Table to group casualties by road surface conditions.

Visualization:

Used a Treemap to visualize the proportion of casualties across wet, dry, and snow/ice conditions.

## Insights
Dry Roads:

Account for the majority of casualties (279,445), likely due to higher traffic volumes and speeds.

Wet Roads:

Still significant (115,261), indicating that adverse weather conditions contribute to a substantial number of accidents.

Snow/Ice:

Represented a smaller but notable portion of casualties (22,781), emphasizing the dangers of icy or snowy road conditions.

## Key Insights
Dry roads are the most dangerous in terms of absolute casualties, likely due to higher traffic density and speed.

Wet roads contribute significantly to accidents, highlighting the need for weather-specific safety measures.

Snow/ice conditions, while less frequent, still pose a serious risk, especially in regions with harsh winters.

## Actionable Steps
For Dry Roads:

Focus on speed management, driver awareness, and traffic enforcement.

For Wet Roads:

Improve road drainage, promote tire safety, and increase driver education on wet-weather driving.

For Snow/Ice:

Enhance winter road maintenance (e.g., salting, plowing), promote winter tire usage, and educate drivers on safe driving in icy conditions.

## Casualties by Location/Area
## Description
This analysis breaks down road accident casualties by location, comparing rural and urban areas.

The data includes:

Rural Areas: 162,000 casualties

Urban Areas: 255,900 casualties

![Screenshot 2025-02-16 085919](https://github.com/user-attachments/assets/0cc5b3ec-df2c-4451-85f4-04b9768896c9)

## How It Was Done
Data Preparation:

Cleaned and categorized the dataset by location (rural vs. urban).

Pivot Table Setup:

Created a Pivot Table to group casualties by location.

Visualization:

Visualized the data using a Pie Chart to show the proportion of casualties in rural vs. urban areas.

## Insights
Urban Areas:

Account for 61.2% of total casualties (255,900 out of 417,900).

Likely due to higher population density, traffic congestion, and frequent intersections.

Rural Areas:

Account for 38.8% of total casualties (162,000 out of 417,900).

Often attributed to higher speeds, poor road conditions, and limited access to emergency services.

## Key Insights
Urban areas have a higher proportion of casualties, reflecting the challenges of dense traffic and complex road networks.

Rural areas, while less populated, still contribute significantly to casualties, often due to riskier driving behaviors and infrastructure limitations.

## Actionable Steps
For Urban Areas:

Improve traffic management systems (e.g., traffic lights, pedestrian crossings).

Promote public transportation to reduce congestion.

Increase enforcement of traffic laws (e.g., speeding, drunk driving).

For Rural Areas:

Enhance road infrastructure (e.g., better signage, and road maintenance).

Implement speed limits and safety campaigns targeting rural drivers.

Improve emergency response times in remote areas.

## Casualties by Light Condition
## Description
This analysis breaks down road accident casualties by light conditions, comparing daylight and dark environments.

The data includes:

Daylight: 112,900 casualties

Dark: 305,000 casualties

![Screenshot 2025-02-16 085942](https://github.com/user-attachments/assets/b950418b-ecc7-41cf-811d-2a55f2156c05)

## How It Was Done
Data Preparation:

Cleaned and categorized the dataset by light conditions (daylight vs. dark).

Pivot Table Setup:

Created a Pivot Table to group casualties by light conditions.

Visualization:

Visualized the data using a Pie Chart to show the proportion of casualties in daylight vs. dark conditions.

33 Insights
Dark Conditions:

Account for 73.0% of total casualties (305,000 out of 417,900).

Likely due to reduced visibility, driver fatigue, and increased risk-taking behaviors at night.

Daylight Conditions:

Account for 27.0% of total casualties (112,900 out of 417,900).

Despite better visibility, accidents still occur due to factors like higher traffic volumes and driver distractions.

## Key Insights
The majority of casualties occur in dark conditions, highlighting the significant impact of reduced visibility on road safety.

Daylight conditions, while safer in terms of visibility, still contribute to a notable number of accidents.

## Actionable Steps
For Dark Conditions:

Improve street lighting in high-risk areas.

Promote the use of reflective clothing and vehicle lighting.

Increase enforcement of traffic laws during nighttime (e.g., drunk driving, speeding).

For Daylight Conditions:

Focus on reducing driver distractions (e.g., mobile phone usage).

Enhance traffic management systems to handle higher traffic volumes.

Promote awareness campaigns targeting daytime driving risks.

## Filter Panel Overview
## Description
The slicer allows filtering road accident data by:

Accident Date: 2021, 2022.

Urban/Rural Location: Rural, Urban.

![Screenshot 2025-02-16 090019](https://github.com/user-attachments/assets/10742ddc-3d7c-49b8-8320-db3e63b975e6)

## Key Insights
By Year (2021 vs. 2022):

Compare casualties between 2021 and 2022 to identify trends.

By Location (Rural vs. Urban):

Compare casualties in Rural vs. Urban areas for 2021 and 2022.

## Total Casualties by Vehicle Type
## Description
This screenshot presents a visual representation of the total casualties categorized by different vehicle types. The data is displayed in a clear and concise manner, making it easy to interpret the impact of each vehicle type on overall casualties.

![Screenshot 2025-02-16 090155](https://github.com/user-attachments/assets/8b31150e-9643-4d39-a45a-50221db853fe)

## Insights:
The vehicle type with the highest number of casualties is represented by the value 333,485, indicating a significant impact.

Other vehicle types show varying levels of casualties, with the lowest being 1,032.

This visualization helps in identifying which vehicle types may require more attention in terms of safety measures and regulations.

## Navigation Icons
## Description
This screenshot showcases a set of navigation icons designed to enhance user interaction and provide quick access to various resources related to the project. Each icon serves a specific purpose, facilitating seamless navigation and access to additional information.

![Screenshot 2025-02-16 090325](https://github.com/user-attachments/assets/18b16a0d-a6e1-4e74-8b67-3fdae40319f4)

## Icon Functions:
## Dashboard Icon:

Function: Clicking on this icon redirects the user to the main dashboard.

Purpose: Provides a quick return to the primary interface where key metrics and visualizations are displayed.

## Data Analyst Sheet Icon:

Function: This icon links directly to the data analyst sheet within the Excel workbook.

Purpose: Allows users to access and review the raw data and detailed analysis performed in the Excel workbook.

## Email Icon:

Function: Clicking this icon opens the default email client with a pre-addressed email to the project contact.

Purpose: Facilitates easy communication with the project team for inquiries or feedback.

## Wikipedia Icon:

Function: This icon redirects the user to the Wikipedia page on UK road accidents.

Purpose: Provides additional context and background information on road accident statistics and trends in the UK.







