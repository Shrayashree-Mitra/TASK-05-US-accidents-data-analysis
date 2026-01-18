# TASK-05-US-accidents-data-analysis
Analysis and visualization of a large scale US Accidents dataset involving data cleaning, column selection, feature preparation, and insight generation using Python and Power BI.

### CLEANED DATASET
due to file size restrictions,the cleaned dataset can be downloaded here:
### POWER BI DASHBOARD
the'.pbix' file is available here:


# US Accidents Data Analysis

This repository contains a complete data analysis project performed on the US Accidents dataset.  
The project focuses on data cleaning, column selection, feature preparation, and visualization using Python and Power BI.

The objective is to transform a large real-world dataset into an analysis-ready format and extract meaningful insights related to accident severity, weather conditions, time patterns, and traffic infrastructure.

## Dataset Overview

The dataset used in this project is the *US Accidents Dataset*, which contains records of traffic accidents across the United States.  
Due to the large size of the dataset, efficient data handling techniques were applied.

## Tools & Technologies Used

- Python (Pandas, NumPy)
- Jupyter Notebook / VS Code
- Power BI
- GitHub

## Project Tasks Overview

### Task 1: Dataset Understanding
- Reviewed dataset structure and column definitions
- Identified relevant variables for analysis

### Task 2: Data Cleaning
- Handled missing values
- Removed duplicate records
- Corrected data types
- Filtered invalid values

### Task 3: Exploratory Data Analysis
- Analyzed accident severity distribution
- Explored relationships between weather conditions and accidents
- Identified time-based accident patterns

### Task 4: Data Visualization (Power BI)
- Created interactive dashboards
- Used KPIs, bar charts, donut charts, and filters
- Visualized severity, weather impact, and survival-related insights

### Task 5: Dataset Column Selection & Feature Preparation
- Reduced dataset size using column selection
- Loaded data in chunks to handle large file efficiently
- Selected features relevant to severity, weather, time, and infrastructure
- Prepared cleaned dataset for analysis and visualization

## Task 5 – Detailed Explanation

### Objective
To optimize the dataset by selecting only relevant columns and ensuring high-quality data for further analysis.

### Selected Columns
    "ID",
    "Start_Time",
    "Severity",
    "Temperature(F)",
    "Visibility(mi)",
    "Wind_Speed(mph)",
    "Humidity(%)",
    "Precipitation(in)",
    "Weather_Condition",
    "Traffic_Signal",
    "Junction",
    "Crossing",
    "Stop",
    "Sunrise_Sunset"

These features support analysis related to:
- Accident severity
- Weather impact
- Time-based trends
- Day vs night accidents
- Infrastructure influence

### Data Cleaning Steps
- Converted Start_Time to datetime format
- Removed duplicate accident records using ID
- Dropped records with missing critical values
- Removed invalid negative values in weather-related columns
- Standardized categorical values for consistency



## Key Insights
- Accident severity varies significantly based on weather conditions and visibility
- A higher number of accidents occur during daytime, but severity increases during night hours
- Weather factors such as precipitation and low visibility contribute to increased accident risk
- Presence of traffic signals influences accident frequency and severity distribution
- A higher number of accidents occur during daytime, but severity increases during night hours
- Weather factors such as precipitation and low visibility contribute to increased accident risk
- Presence of traffic signals influences accident frequency and severity distributio
