# UK-Road-Accident-Analysis-Dashboard
# Executive Summary

Road safety remains one of the most critical public policy issues in the United Kingdom. With thousands of casualties each year, understanding the factors contributing to road accidents can save lives, reduce injuries, and improve infrastructure planning.

This UK Road Accident Dashboard project provides a comprehensive analysis of road accident data across the UK using an interactive dashboard built in Microsoft Excel (and optionally Power BI). It explores patterns, trends, and contributing factors that influence accident frequency and severity.

The project leverages real-world accident records, highlighting critical insights such as:

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
Tools Used	Microsoft Excel (Power Query, Pivot Tables, Charts, Dashboard), optionally Power BI
Data Source	UK Department for Transport (open dataset on road safety)
Time Period Covered	2022 (as per dataset sample)
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

Includes summarized KPIs and pivot-table-ready metrics such as:

Total number of accidents

Total casualties

Average casualties per accident

Segregations by severity, weather, and lighting

Breakdown of vehicle involvement and road condition impacts

3. Dashboard

Interactive visualization panel combining:

Dynamic filters for month, year, region, or vehicle type

Charts for:

Casualty count by road surface

Accident frequency by time of day

Severity analysis by weather condition

Distribution of accidents by urban/rural area

KPI cards showing:

Total accidents

Fatalities

Serious & Slight injuries

Percentage distribution across categories

# Methodology

Data Collection:
Data imported from UK Department for Transport’s open database (via CSV/Excel).

Data Cleaning & Preparation:

Removed null and duplicate records.

Standardized column names and data types.

Converted date-time columns for temporal analysis.

Derived new features (Month, Year, Day of Week).

Data Modeling:

Created structured tables for accident details, vehicle details, and aggregated KPIs.

Established relationships for dashboard filtering and slicing.

Dashboard Development:

Built KPI cards for quick insight.

Developed bar, line, and donut charts for comparative visualizations.

Implemented slicers for interactive filtering.

Added conditional formatting to highlight high-risk trends.

# Key Insights

Weather Conditions: Majority of accidents occurred under clear conditions, suggesting human error as a major factor.

Lighting Conditions: A significant proportion of severe accidents occurred in dark but lit conditions (e.g., at night in urban areas).

Vehicle Type: Cars dominate accident involvement, but motorcycles have a higher fatality rate per accident.

Road Surface: Most accidents occurred on dry surfaces, but wet roads had proportionally higher severity.

Urban vs Rural: Urban areas recorded more accidents, but rural accidents tend to be more severe.

Peak Time: Evenings (4–7 PM) and weekends show the highest accident frequency.

# Key Performance Indicators (KPIs)
KPI	Value (Example from Dataset)	Description
Total Casualties	417,883	Total number of casualties reported
Total Accidents	300,000+	Number of unique accidents recorded
Average Casualties per Accident	~1.4	Average number of people injured per incident
Most Common Severity	Slight	Majority of accidents were minor
Most Common Road Type	Single Carriageway	Most frequent setting for reported accidents

# Recommendations

Enhance Road Lighting: Improve illumination in semi-lit urban zones.

Public Awareness Campaigns: Focus on defensive driving and speeding awareness.

Weather Alert Systems: Real-time driver alerts for slippery or foggy conditions.

Infrastructure Improvement: Target high-frequency accident junctions for redesign.

Speed Regulation Enforcement: Increase patrols and smart cameras in rural zones.

# Future Scope

Integrate Power BI / Tableau for advanced interactivity.

Build a predictive model to estimate accident severity based on environmental factors.

Add geospatial visualization (e.g., heatmaps for accident hotspots).

Automate monthly updates using Power Query connections to live datasets.



# Conclusion

This project delivers a data-driven, visual exploration of UK road accidents that can directly support policy formulation, driver education, and infrastructure design.
By providing actionable insights into when, where, and why accidents occur, the analysis contributes toward the UK’s Vision Zero initiative — aiming for zero road fatalities in the long term.
