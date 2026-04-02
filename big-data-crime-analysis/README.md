# Big Data Crime Analysis Using Apache Spark

## Overview
This project analyses large-scale UK crime data using Apache Spark to evaluate claims about burglary trends, firearms incidents, and the relationship between firearms and drug-related offences.

## Objectives
- Examine whether burglary rates are increasing over time
- Determine whether Liverpool has the highest firearms incident rate per capita
- Investigate whether firearms incidents are associated with drug offences

## Dataset
This project uses multiple public datasets, including:
- UK Street Level Crime Data
- English Indices of Deprivation
- LSOA population data
- Postcode or location reference data where required

## Methodology
The analysis was carried out using Apache Spark for large-scale data processing. Key steps included:
- Data cleaning and preprocessing
- Aggregation by month and geographic area
- Time series analysis of burglary trends
- Per capita calculation of firearms incidents using population data
- Correlation analysis between firearms incidents and drug offences

## Key Findings
- Burglary showed an overall decreasing trend over the study period
- Liverpool did not have the highest firearms incident rate per capita
- The analysis found a moderate negative correlation between firearms incidents and drug offences

## Tools and Technologies
- Apache Spark
- PySpark
- Python
- Pandas
- Matplotlib

## Project Notebook
[View Notebook](./big-data-crime-analysis.ipynb)
