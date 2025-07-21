# COVID-19 Analysis: Germany

This project focuses on analyzing COVID-19 data specific to Germany, using a dataset from Our World in Data. The goal was to explore trends in cases, deaths, and vaccinations through data cleaning, transformation, and visualization.

## Project Overview

The analysis includes:

- Cleaning and filtering a large dataset for Germany
- Handling missing values using forward fill techniques
- Converting date formats and selecting relevant columns
- Creating new columns such as:
- Active cases (total cases - total deaths)
- 7-day rolling average of new cases
- Vaccination coverage as a percentage of the population

## Data Source

The data was taken from 'Our World in Data' (https://ourworldindata.org/covid-deaths) and saved locally as `covid-data.csv`.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Visualizations

The project includes several types of visualizations to make the trends easier to understand:

- Line plots showing daily and total COVID cases over time
- Bar charts for new deaths and rolling averages
- Donut and pie charts to represent vaccination status

## Skills Demonstrated

- Data cleaning and transformation
- Exploratory data analysis (EDA)
- Data visualization with multiple libraries
- Feature engineering to add real-world insights
- Writing clean, well-commented Python code

## Folder Structure

covid-germany-analysis/
├── covid_analysis.ipynb
├── data/
│ └── covid-data.csv
└── README.md

## Author

Jay Bhadiyadra
(https://github.com/jaybhadiyadra4)
