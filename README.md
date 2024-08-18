# Bike-Sharing Trends Analysis Q1 2024 - Tableau Project

## Overview
This Tableau project analyzes bike-sharing patterns in our city for the first quarter of 2024 (January to March). The project aims to provide insights into popular stations, rider behaviors, and differences between member and casual riders.

## Project Structure

### 1. Main Workbook
- **Tableau Public Link:** [BikeShare Q1 2024 Analysis](https://public.tableau.com/app/profile/michael.andia/viz/Citibike20241stQAnalysis/2024Q1Overview?publish=yes)
- **Description:** The primary Tableau workbook containing all visualizations and data connections.
- **File:** `Citibike 2024 1st Q Analysis.twb`

### 2. Data Source

The original data for this project was sourced from multiple files available at:
[Citi Bike System Data](https://citibikenyc.com/system-data)

Specifically, we used the following datasets:
- JC-202401-citibike-tripdata.csv
- JC-202402-citibike-tripdata.csv
- JC-202403-citibike-tripdata.csv

The final dataset after processing for the Tableau visualizations:

- **File:** `1st_quarter_bike_data.csv`
- **Description:** This CSV file contains the cleaned and consolidated data from all three months, serving as the primary data source for the Tableau project.

For data integrity and reproducibility, both the original datasets and the data processing notebook are included in the project repository.

### 3. Data Cleaning

- **File:** `Data_Cleaning.ipynb`
- **Description:** This notebook contains the Python code used to clean, process, and merge the original datasets into a single comprehensive CSV file.

### 4. Supplementary Analysis
- **File:** `Analysis of Bike-Sharing Trends in Q1 2024.md`
- **Description:** A detailed written report explaining the findings and interpretations of the visualizations.

## Key Visualizations

1. **Station Popularity Map**
   - Interactive map showing the most frequented start and end stations.

2. **Ride Statistics Dashboard**
   - Overview of key metrics including total rides, average duration, and popular routes.

3. **Member vs. Casual Rider Comparison**
   - Side-by-side analysis of usage patterns between member and casual riders.

4. **Weekly Usage Heatmap**
   - Visualization of peak usage times throughout the week.

5. **Quarterly Trend Chart**
   - Line graph showing daily ride counts for members and casual riders from January to March.

## How to Access the Project

This project is hosted on Tableau Public. You can view and interact with the visualizations using the following link:

[BikeShare Q1 2024 Analysis](https://public.tableau.com/app/profile/michael.andia/viz/Citibike20241stQAnalysis/2024Q1Overview?publish=yes)

## Using This Project

1. Click the link above to access the Tableau Public visualization.
2. Use the navigation tabs at the top to switch between different views and dashboards.
3. Interact with filters and parameters to explore specific aspects of the data.
4. Hover over data points for additional details.
