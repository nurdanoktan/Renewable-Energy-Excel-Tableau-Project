# Renewable-Energy-Excel-Tableau-Project

![image](https://github.com/nurdanoktan/Renewable-Energy-Excel-Tableau-Project/assets/112075689/ff87fc58-c5fe-4f89-ace3-48aa19189bce)

**[Explore the Dashboard](https://public.tableau.com/app/profile/nurdan.oktan/viz/Renewable_Energy_by_Countries/Dashboard1)**

## Overview

This repository contains a comprehensive analysis of global renewable energy production based on the dataset obtained from [Kaggle](https://www.kaggle.com/datasets/programmerrdai/renewable-energy), the data source is IRENA. The data has been cleaned and transformed into an interactive Tableau dashboard, providing valuable insights into renewable energy trends. `renewable_energy_dataset.zip` includes the original and cleaned and extracted data.

## Purpose

The purpose of this project is to deliver an in-depth and interactive exploration of renewable energy data, offering valuable insights into worldwide renewable energy production, country-specific patterns, and the pivotal role of hydroelectric energy. 

## Data Preparation

In the process of creating the Renewable Energy Dashboard, data preparation was conducted to ensure the accuracy and completeness of the visualizations. This involved several steps, including:

1. **Geothermal Energy Data Enhancement**: The geothermal energy dataset, initially containing country names and lacking geographical coordinates (latitude and longitude), was enriched to include location information. A secondary table, sourced from the internet and containing country names along with their respective latitude and longitude values, was integrated into the geothermal energy dataset.

2. **Latitude and Longitude Columns**: New columns for latitude and longitude were created within the geothermal energy dataset to accommodate the additional location data.

3. **VLOOKUP for Location Data**: To populate the newly added latitude and longitude columns, a **VLOOKUP** operation was meticulously performed. This operation cross-referenced the country names in the geothermal dataset with the corresponding latitude and longitude values from the secondary dataset. Any discrepancies or missing values were systematically addressed during this process, ensuring the accuracy of the location data.

4. **Top 10 Renewable Sources by Country (2021)**: Specific data extraction was conducted to identify and visualize the top 10 countries for wind, hydro, solar, and other renewable sources in the year 2021. This data was extracted from the main dataset to create insightful visualizations in Tableau.

5. **Quality Control**: Rigorous data quality checks were conducted to identify and rectify any inconsistencies in country names, address outdated designations, and accurately add latitude and longitude values for countries not originally included in the reference dataset.

The meticulous data preparation process ensured that the geothermal energy data was enhanced with precise geographical coordinates, facilitating accurate mapping and exploration of geothermal energy capacity across different countries in the dashboard.


## Dashboard Visualizations

The interactive dashboard includes the following visualizations:

1. **Global Renewable Energy Production**: An overview of global renewable energy production.
2. **Renewable Energy Production by Countries**: Detailed insights into renewable energy production using filter by country and year.
3. **% of Total Renewable Energy Production by Countries**: A percentage breakdown of renewable energy sources using filter by country and year.
4. **Top 10 Countries Producing Electricity from Hydro in 2021**: Ranking of countries by hydroelectric energy production in 2021.
5. **Top 10 Countries Producing Electricity from Solar in 2021**: Ranking of countries by solar energy production in 2021.
6. **Top 10 Countries Producing Electricity from Wind in 2021**: Ranking of countries by wind energy production in 2021.
7. **Top 10 Countries Producing Electricity from Other Sources in 2021**: Ranking of countries by renewable energy production from sources other than hydro, solar, and wind in 2021.
8. **Renewables (% Primary Energy Equivalent) by Countries**: Visualization of the percentage of renewables in the primary energy mix for various countries using filter by year.
9. **Renewables (% Primary Energy Equivalent) between 1965 - 2021**: Analysis of renewable energy trends between 1965 and 2021 using filter by country.
10. **Biofuels Production by Countries**: A comprehensive view of biofuels production by different countries.
11. **Geothermal Capacity of Countries**: A comparison of geothermal energy capacity among countries.

## Key Insights

Here are some key insights from the renewable energy data:

- In 2021, China emerged as the leading producer of renewable energy from wind, solar, and other sources, including biofuels.

- Japan excelled in producing electricity from hydro sources in 2021, ranking as the top hydroelectric energy producer.

- Hydroelectric energy dominated the global renewable energy landscape, accounting for a significant portion of the total energy produced in 2021 with 4,230 TWh.

- Norway led the way in renewable energy adoption, with renewables constituting an impressive 71% of its primary energy equivalent in 2021.
