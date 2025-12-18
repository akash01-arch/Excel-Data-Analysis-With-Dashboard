# Excel-Data-Analysis-With-Dashboard
# Road Accident Analysis Dashboard (2021-2022)

## Project Overview
This project involves a comprehensive analysis of over 300,000 road accident records to identify key safety trends and contributing factors. Using **Advanced Excel** and **Power Query**, I transformed raw, fragmented data into an interactive decision-making tool.

![Dashboard Screenshot](Screenshots/dashboard_main.png) 
*Replace this with your actual screenshot link once uploaded*

## The Problem (Data Challenges)
The raw dataset contained several inconsistencies that required advanced ETL (Extract, Transform, Load) techniques:
- **Inconsistent Text:** Trailing spaces in categories (e.g., "Darkness " vs "Darkness").
- **Missing Values:** Over 1,500 records with missing `Road_Type` and `Road_Surface_Conditions`.
- **Date Formatting:** Raw data required conversion into a standardized Date Table to enable Year-over-Year (YoY) comparison.

## Technical Skills Applied
- **Power Query (M-Language):** - Automated data cleaning pipeline.
  - Applied conditional logic to group vehicle types.
  - Used "Trim" and "Clean" functions to ensure data integrity.
- **Data Modeling:** Built a star-schema-like structure using Pivot Tables to handle 307,973 rows efficiently.
- **DAX-style Logic in Excel:** Created custom calculated fields for Casualty Growth and Severity Distribution.
- **UI/UX Design:** Implemented a dark-themed, professional interface with interactive Slicers and Timelines.

## Key Insights
- **Casualty Volume:** Cars represent the highest percentage of casualties (~80%), followed by Goods Vans.
- **Severity Factors:** While most accidents occur in daylight, the ratio of "Serious" to "Slight" accidents increases significantly during adverse weather (Ice/Snow).
- **Urban vs Rural:** Rural accidents tend to have a higher casualty count per incident compared to Urban areas.

## How to View
1. Download the `Road_Accident_Analysis.xlsx` file.
2. Open in Microsoft Excel (Enable Macros/Content if prompted for Power Query).
3. Use the Slicers on the left to filter by Year, Weather, or Road Type.

---
**Author:** [Akash More]  
**Tools:** Excel | Power Query | Pivot Tables
