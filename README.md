# UK-Road-Accident-Analysis-Dashboard
# Executive Summary

Road safety remains one of the most critical public policy issues in the United Kingdom. With thousands of casualties each year, understanding the factors contributing to road accidents can save lives, reduce injuries, and improve infrastructure planning. As per statistics - https://en.wikipedia.org/wiki/Reported_Road_Casualties_Great_Britain 

This UK Road Accident Dashboard project provides a comprehensive analysis of road accident data across the UK using an interactive dashboard built in Microsoft Excel. It explores patterns, trends, and contributing factors that influence accident frequency and severity.

The project leverages real-world accident 307974 records, highlighting critical insights such as

Time-based accident trends (monthly, daily, and hourly distributions)

Impact of road and weather conditions

Casualty severity by vehicle type and road surface

Geographical segmentation (Urban vs Rural)

Identification of high-risk conditions and areas

Ultimately, this project aims to empower decision-makers—including transport authorities, policymakers, and researchers—with data-driven insights to improve road safety policies and prevent future incidents.

# Project Overview
Component	Description
Project Title	UK Road Accident Dashboard
Objective	To analyze road accident trends, identify high-risk conditions, and provide actionable insights for improving road safety.
Tools Used	Microsoft Excel (Power Query, Pivot Tables, Charts, Dashboard)
Data Source	UK Department for Transport (open dataset on road safety)
Time Period Covered	2021 & 2022 (as per dataset sample)
Key Deliverable	Interactive dashboard summarizing accident trends and severity distribution

 #Data Description

The dataset includes multiple sheets, each serving a unique purpose:

1. Detail1

Contains detailed accident-level information with the following columns:

Column	Description
Accident_Index	Unique identifier for each recorded accident
Accident_Date	Date when the accident occurred
Month / Year / Day_of_Week	Time dimensions for trend analysis
Junction_Control	Type of junction (e.g., Give Way, Roundabout)
Junction_Detail	Specifies accident proximity to junctions
Accident_Severity	Categorical variable (Slight / Serious / Fatal)
Latitude / Longitude	Geographical coordinates
Light_Conditions	Daylight or Night
Number_of_Casualties	Total casualties per accident
Number_of_Vehicles	Vehicles involved in the accident
Police_Force	Regional jurisdiction reporting the accident
Road_Surface_Conditions	Dry, Wet/Damp, Frost, etc.
Road_Type	Single, Dual Carriageway, Roundabout, etc.
Speed_limit	Speed limit where the accident occurred
Urban_or_Rural_Area	Area type classification
Weather_Conditions	Environmental factors at the time of incident
Vehicle_Type	Category of vehicle involved (e.g., Car, Motorcycle, Bicycle, HGV, Agricultural vehicle)

2. Data Analytics Sheet

Includes summarized primary and secondary KPIs and pivot-table-ready metrics such as:

# KPI's
Total casualties
Total Number of fatal, Serious and Slight Accidents.
Total Number of vehicle types by casualties

# Pivot tables
Segregations by severity - fatal, serious, slight in % and total numbers.
Segergations by Urban and Rural area type.
Segergation by Light conditions.
Segergation by Road Type and Road surface.
Segergation by Monthy trend and Time analysis.

# Process
- Cleaned the data for anamolies and wrong text formats. Replaced values to correct values. 
- Converted the sheet into table for pivot charts and data analysis.
- Calculated the below by pivot chart and excel formulas for visualization - 
- Total number of casualties.
- Total number of casualties by severtiy - fatal, serious and slight.
- Total number of casaulties by year (2021 and 2022)
- Total number of casaulties by Road Type.
- Total number of casualties by Road surface.
- Total number of casualties by Area.
- Total number of casualties by Light conditions.
- Total number of casualties by Time analysis.
- Created slicers by year, area type, accident dates for filtering the report.
- Created structured tables for accident details, vehicle details, and aggregated KPIs.
- Established relationships for dashboard filtering and slicing



# Interactive visualization panel combining:

Dynamic filters for year, area and accident dates

KPI Cards -
Total count  for total number of casualties.
Total count and pie chart for Fatal Casualties. Percentage distribution across categories.
Total count and pie chart for Serious Casualties
Total count and pie chart for Slight Casualties
Total count and pie chart for Casualties By Car.

Secondary KPI Card -
Total count for casualties By Car - 177681
Total count for casualties By Bus = 6225
Total count for casualties By Bike - 18093
Total count for casualties By Others - 1974
Total count for casualties By Van - 17567
Total count for casualties By Agriculture vehicle - 633.

Charts for:

Line Chart to showcase casualties by Year.
Clustered columns chart to showcase casualties by Road Type.
Tree map to showcase casualties by Road surface.
Pie chart to showcase casualties by area.
Pie chart to showcase casualties by Light conditions.
Area chart to showcase casualties by Time analysis.


# Dashboard Development:

- Built KPI cards for quick insight.
- Developed bar, line, and donut charts for comparative visualizations.
- Implemented slicers for interactive filtering.
- Added conditional formatting to highlight high-risk trends.

# Key Insights
- Weather Conditions: Majority of accidents occurred under clear conditions, suggesting human error as a major factor.
- Lighting Conditions: A significant proportion of severe accidents occurred in dark but lit conditions (e.g., at night in urban areas).
- Vehicle Type: Cars dominate accident involvement, but motorcycles have a higher fatality rate per accident.
- Road Surface: Most accidents occurred on dry surfaces, but wet roads had proportionally higher severity.
- Urban vs Rural: Urban areas recorded more accidents, but rural accidents tend to be more severe.
- Peak Time: Evenings (4–7 PM) and weekends show the highest accident frequency.

# Key Performance Indicators (KPIs)
# KPI	Value
- Total Casualties	417,883	Total number of casualties reported
- Total Accidents	300,000+	Number of unique accidents recorded
- Most Common Severity	Slight	Majority of accidents were minor
- Most Common Road Type	Single Carriageway	Most frequent setting for reported accidents

# Recommendations
- Enhance Road Lighting: Improve illumination in semi-lit urban zones.
- Public Awareness Campaigns: Focus on defensive driving and speeding awareness.
- Weather Alert Systems: Real-time driver alerts for slippery or foggy conditions.
- Infrastructure Improvement: Target high-frequency accident junctions for redesign.
- Speed Regulation Enforcement: Increase patrols and smart cameras in rural zones.


# Conclusion

This project delivers a data-driven, visual exploration of UK road accidents that can directly support policy formulation, driver education, and infrastructure design.
By providing actionable insights into when, where, and why accidents occur, the analysis contributes toward the UK’s Vision Zero initiative aiming for zero road fatalities in the long term.
