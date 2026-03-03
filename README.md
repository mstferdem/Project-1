# Project 1 
# College Recruitment Improvement Study


## Computing Majors Survey Analysis (2020-2024)
## Purpose of the Project
The primary goal of this project is to explore, clean, and analyze survey data from students enrolled in computing majors at the County College of Morris (CCM). This analysis spans five years (Fall 2020 to Fall 2024) and aims to provide insights into student demographics, degree interests, and the effectiveness of recruitment channels. By standardizing and merging individual survey years, the project identifies trends in student motivations and the factors influencing their decision to attend CCM.

## Research Questions
This project aims to answer the following questions:

- Which degree programs show the greatest increase or decrease in the percentage of student interest over the years based on survey responses?

- How has the percentage distribution of female students by degree program changed over time?

- How has the percentage distribution of male students by degree program changed over time?

- Which factors had the greatest impact on students' decision to attend CCM?

- How has the way students hear about CCM changed over the years?

## Repository Contents
# Analysis and Code
project1.ipynb: The main Jupyter Notebook containing the Python code for the data cleaning process. It standardizes long survey question text into shorter, manageable column names (e.g., heard_from_..., decision_impact_...), handles data types, and concatenates individual annual CSV files into a unified dataset for analysis.

## Datasets
- Majors Survey Results - Fall 2020.csv: Raw survey data collected during the Fall 2020 semester.

- Majors Survey Results - Fall 2021.csv: Raw survey data collected during the Fall 2021 semester.

- Majors Survey Results - Fall 2022.csv: Raw survey data collected during the Fall 2022 semester.

- Majors Survey Results - Fall 2023.csv: Raw survey data collected during the Fall 2023 semester.

- Majors Survey Results - Fall 2024.csv: Raw survey data collected during the Fall 2024 semester.

- New Majors Survey Results - Fall 2020-2024.csv: The final output of the data processing pipeline. This file is a consolidated and cleaned version of all five years of survey data, featuring standardized column headers and consistent data formats ready for visualization.

## Data Standardized in this Project
- The cleaning process creates a structured dataset with the following key metrics:

- Recruitment Sources: Standardized columns indicating how students heard about CCM (e.g., Web site, Social Media, High School Counselor).

- Decision Impact Factors: Measures of how factors like affordable cost, location, and choice of programs influenced student enrollment.

-Demographics: Standardized values for gender and current degree programs to allow for longitudinal comparison.
