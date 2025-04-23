# Crime Data Analysis - Montgomery County

This repository contains a comprehensive analysis of crime data in Montgomery County, Maryland, sourced from Kaggle's National Incident-Based Reporting System (NIBRS) dataset. The analysis aims to uncover key crime patterns, trends, and insights, using data from 2018 to 2022. The findings are intended to guide law enforcement strategies, optimise resource allocation, and improve community safety.

## Contents

1. **Data Preprocessing & Cleaning**
   - This project includes an in-depth cleaning process for handling missing values, duplicate entries, and irrelevant columns.
   - Key columns, such as 'Dispatch Date/Time' and 'Block Address,' were cleaned for accuracy, and insignificant data points were removed.

2. **Exploratory Data Analysis (EDA)**
   - The data undergoes various transformations to prepare it for analysis, including normalisation, handling null values, and converting time-related data into consistent formats.
   - EDA techniques help identify important patterns and insights, such as common crime types, high-crime districts, and trends over time.

3. **Key Findings**
   - **High-Crime Districts:** Identifies areas like Silver Spring and Montgomery Village with the highest crime rates, assisting in targeted law enforcement strategies.
   - **Crime Trends:** Analysis of crime over time shows a decrease in overall crime but an increase in specific categories such as larceny and drug violations post-pandemic.
   - **Time-Based Analysis:** Peak crime times and days (e.g., late-night and Fridays) are identified to help optimise police presence.
   - **Crime Type Distributions:** The dataset reveals significant findings such as marijuana possession being the dominant drug-related offence.

4. **Visualisations**
   - The repository includes various visualisations such as heatmaps, bar charts, and line graphs that depict crime frequency across different times of the day, locations, and crime types. These tools provide actionable insights for both law enforcement and policy makers.
   
5. **Tools & Libraries Used**
   - **Python Libraries:** Pandas, Seaborn, Matplotlib, Plotly
   - **Key Techniques:** Data Cleaning, Exploratory Data Analysis, Data Visualisation, Trend Analysis

## Installation

To run this analysis, you will need the following libraries installed:

```bash
pip install pandas seaborn matplotlib plotly
```

You can then load the dataset and begin your analysis using the provided Python scripts.

## Usage

1. **Load Data**: Import the cleaned dataset into your Python environment.
2. **Run EDA**: Use the scripts provided to conduct exploratory data analysis, identifying trends, anomalies, and insights.
3. **Create Visualisations**: Generate heatmaps, bar plots, and other visualisations to further understand crime distribution across Montgomery County.

## Conclusion

The analysis in this repository helps identify key crime hotspots, trends, and correlations within Montgomery County's crime data, supporting more effective law enforcement interventions. By understanding temporal and spatial crime patterns, local police departments can optimise resources and enhance public safety.
