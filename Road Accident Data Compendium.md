# Road Accident Dataset Dictionary

## Overview
This dataset contains detailed records of road accidents, including information on accident severity, location, environmental conditions, and vehicle involvement.

## Column Descriptions

| Column Name                  | Data Type      | Description |
|------------------------------|---------------|-------------|
| `Accident_Index`             | Object        | Unique identifier for each accident record. |
| `Accident Date`              | DateTime      | The date when the accident occurred. |
| `Day_of_Week`                | Object        | The day of the week on which the accident happened (e.g., Monday, Tuesday). |
| `Junction_Control`           | Object        | Type of control present at the junction (if applicable). |
| `Junction_Detail`            | Object        | Detailed description of the junction where the accident took place. |
| `Accident_Severity`          | Object        | Classification of accident severity (e.g., Fatal, Serious, Slight). |
| `Latitude`                   | Float         | Latitude coordinate of the accident location. |
| `Longitude`                  | Float         | Longitude coordinate of the accident location. |
| `Light_Conditions`           | Object        | Lighting conditions at the time of the accident (e.g., Daylight, Darkness). |
| `Local_Authority_(District)` | Object        | The local governing authority responsible for the accident location. |
| `Carriageway_Hazards`        | Object        | Any hazards present on the carriageway at the time of the accident. |
| `Number_of_Casualties`       | Integer       | Total number of casualties involved in the accident. |
| `Number_of_Vehicles`         | Integer       | Number of vehicles involved in the accident. |
| `Police_Force`               | Object        | Police force responsible for recording the accident. |
| `Road_Surface_Conditions`    | Object        | Condition of the road surface at the time of the accident (e.g., Dry, Wet, Snow). |
| `Road_Type`                  | Object        | Type of road where the accident occurred (e.g., Single carriageway, Dual carriageway). |
| `Speed_limit`                | Integer       | Speed limit (in mph) of the road where the accident took place. |
| `Time`                       | Object        | Time of the accident. |
| `Urban_or_Rural_Area`        | Object        | Whether the accident occurred in an urban or rural area. |
| `Weather_Conditions`         | Object        | Weather conditions at the time of the accident (e.g., Clear, Rain, Fog). |
| `Vehicle_Type`               | Object        | Type of vehicle(s) involved in the accident. |
