# COVID-19 Mobility Analysis Project

## Overview
This project analyzes the relationship between COVID-19 data and mobility trends. The goal is to evaluate the impact, trend, and correlation between COVID-19 cases/deaths and mobility across various locations such as residential areas, workplaces, parks, and more.

## Files
- `bmuvunyi_project.csv`: Contains the processed dataset used for analysis.
- `rw-mobility-covid-data.csv`: The original dataset with raw mobility and COVID-19 data.
- `Project_COVID_MOBILITY.ipynb`: Jupyter Notebook containing the analysis and visualizations.

## Preprocessing
The preprocessing phase included:
- Removing irrelevant columns.
- Dropping columns with more than 80% missing values.
- Handling missing values by replacing them with zero.
- Rescaling the dataset to ensure meaningful visualizations.

## Analysis
Key findings include:
- **Residential Mobility**: Increased with rising COVID-19 cases due to lockdowns and curfews.
- **Transit, Workplace, and Parks**: Showed decreased activity with rising COVID-19 cases, with activity increasing as restrictions eased.
- **Grocery Stores and Pharmacies**: Faced the fewest restrictions and had the most traffic.

## Correlation
- **Positive Correlation**: Residential mobility showed a positive correlation with COVID-19 cases.
- **Negative Correlation**: Other locations such as transit stations and workplaces showed a weak negative correlation with COVID-19 cases.

## Potential Use Cases
- Tracking the effectiveness of government measures.
- Monitoring the spread of contagious diseases based on movement patterns.
- Enhancing the effectiveness of data collection by increasing the frequency to hourly intervals.

## How to Run
To run the analysis:
1. Clone this repository to your local machine.
2. Ensure you have the necessary dependencies installed (`pandas`, `plotly`, `dash`).
3. Open `Project_COVID_MOBILITY.ipynb` in Jupyter Notebook or Jupyter Lab.
4. Execute the cells to reproduce the analysis and visualizations.

## Requirements
- Python 3.10
- pandas
- plotly
- dash
