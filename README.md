# Data Visualisation with Tableau: A Visualisation Analytics Project

## Introduction

This project involves the utilization of Tableau in conducting data analysis and visualization. Two core analyses were performed with the primary goal of identifying patterns across different measurements over time and across different regions. The project further explores relationships between specific measurements.

## Analysis Goals
1. Determine if there are patterns for each measurement over time and across different regions.
2. Ascertain if there are relationships between two or three measurements over time and across different regions.

## Analysis 1: Diabetes Prevalence in West Africa

### Findings

The first analysis is a storyboard highlighting the patterns of Diabetes Prevalence across West Africa, differentiated by Gender and Year. The Storyboard comprises of three worksheets, each presenting different findings:

- **Trend of Diabetes Prevalence Over Time In West Africa:** The graph illustrates a consistent increase in Diabetes prevalence in the West African Region over the years. Mauritania is observed to have the highest prevalence from 1984 to 2014.

- **Forecast of the Prevalence of Diabetes in Top 5 countries in West Africa:** The forecast indicates an expected rise in Diabetes in The Gambia, making it the country with the highest projected Diabetes prevalence in West Africa.

- **Diabetes Prevalence by Gender in Mauritania:** Further analysis shows a higher prevalence of Diabetes in men compared to women in Mauritania.

### Dataset and Attributes

The dataset used is a combination of three tables merged using an inner join, with the primary focus on the Diabetes Table. The Diabetes table contains four attributes: Year, Sex, Country/Region, and Age Standardised Diabetes Prevalence.

### Approach

The goal was to identify any discernible patterns in the Prevalence of Diabetes in West Africa. To achieve this, averages were calculated as the measure 'Age Standardised Diabetes Prevalence' was a ratio. This approach facilitated a proper analysis while search and query functions were used to select countries of note.

## Analysis 2: Impact of Body Mass Index on Raised Blood Pressure

### Findings

The second analysis investigates the relationship between Body Mass Index (BMI) and Raised Blood Pressure. The visualization reveals that men with a lower body mass tend to have higher blood pressure, while women with a higher body mass are more prone to high blood pressure.

### Dataset and Attributes

The dataset consists of three tables: BMI, Raised Blood Pressure, and Diabetes. These tables were merged using Inner join with corresponding keys (Country, Year, Sex). The primary tables for this visualization are the BMI and Raised Blood Pressure tables.

### Approach

This analysis aimed to establish if there is a relationship between BMI and Blood Pressure in West Africa. The insights were derived by calculating the averages of both measures (Raised Blood Pressure and BMI) and plotting them on the Symbols Map. The goal was to compute the averages of the BMI and Raised Blood Pressure Attributes to create a visualization.

## Conclusion

Through these analyses, it's evident that Mauritania has the highest prevalence of Diabetes in West Africa, with men being more affected than women. Meanwhile, The Gambia is projected to have the highest prevalence in the future. Regarding BMI and blood pressure, men with lower body mass are more likely to have high blood pressure, while women with higher body mass tend to experience the same.

## How to Use

1. Clone or download this repository to your local machine.
2. Open the project in Tableau.
3. Navigate through the Storyboard and worksheets to see the analyses and visualizations.
4. Use the filter options to explore the data for different countries and years.
5. Experiment with other datasets to explore the relationships and patterns in your data.

