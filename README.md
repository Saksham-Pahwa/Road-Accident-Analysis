# Road Accident Data Analysis

## Overview
This project presents an interactive dashboard for analyzing road accident data, offering insights into key performance indicators (KPIs), monthly trends, and accident distributions based on road type and surface conditions. It includes in-depth analysis to uncover patterns, correlations, and contributing factors, helping to identify critical areas for improving road safety and decision-making.


## Key Insights

- **Total Casualties Recorded:** 417,883
- **Most Dangerous Road Type:** Roundabouts had the highest number of casualties (26,828).
- **Weather Impact:** Most accidents occurred on **dry roads** (279,445 casualties), followed by **wet roads** (115,261 casualties).
- **Speed Limit Trend:** Most accidents happened on roads with a **30 mph speed limit**.
- **Most Common Light Condition:** The majority of accidents occurred during **daylight** conditions.

## Dataset Description
The dataset contains multiple features describing accident details, including:

| Column Name                  | Description |
|------------------------------|-------------|
| `Accident_Index`             | Unique accident record identifier. |
| `Accident Date`              | Date of the accident. |
| `Day_of_Week`                | Day of the week the accident occurred. |
| `Accident_Severity`          | Categorization into Fatal, Serious, or Slight. |
| `Junction_Control`           | Control type at the junction, if applicable. |
| `Road_Surface_Conditions`    | Dry, Wet, Snow/Ice, etc. |
| `Weather_Conditions`         | Weather impact at the time of the accident. |
| `Number_of_Casualties`       | Total casualties in the accident. |
| `Number_of_Vehicles`         | Vehicles involved in the accident. |
| `Speed_limit`                | Speed limit of the road at the accident location. |
| `Urban_or_Rural_Area`        | Whether the accident occurred in an urban or rural setting. |
| `Vehicle_Type`               | Type of vehicle(s) involved in the accident. |

## Project Files
- **Dataset** - Contains the raw accident data.
- **Dashboard Analysis** - Summarizes insights through data visualizations.
- **Exploratory Data Analysis (EDA)** - Identifies patterns and key metrics.

## Usage
This dataset is useful for:
- Analyzing accident hotspots.
- Identifying risky road/weather conditions.
- Predicting accident severity based on road conditions.

## Tools Used
- **Python** (Pandas, Matplotlib, Seaborn)
- **Excel Dashboard** (for cleaning & dashboard/report creation)

## Conclusion
Understanding road accident data helps in identifying critical factors contributing to accidents. This project provides key insights that can aid policymakers, traffic authorities, and researchers in making data-driven safety improvements.
