
# Crime Data Analysis Project

## Overview
This project involves the analysis of a crime dataset that covers data from 2020 to the present. The dataset includes various details about reported crimes, including dates, times, locations, types of crimes, and more.

## Dataset Description
The dataset (Crime_Data_from_2020_to_Present.csv) consists of the following key columns:

Date Rptd: Date when the crime was reported.
DATE OCC: Date of the crime occurrence.
TIME OCC: Time of the crime occurrence.
AREA: Area code where the crime occurred.
AREA NAME: Name of the area where the crime occurred.
Crm Cd: Crime code.
Crm Cd Desc: Description of the crime.
LOCATION: Location where the crime occurred.
LAT: Latitude coordinate of the crime location.
LON: Longitude coordinate of the crime location.
Additional columns providing further details on each crime incident.


## Data Cleaning and Preprocessing
The data underwent several cleaning and preprocessing steps:

Conversion of date columns to datetime format.
Removal of columns with a significant number of missing values.
Identification and removal of outliers.
Extraction of additional features such as year, month, and day of the week.


## Exploratory Data Analysis (EDA)
The EDA focused on gaining insights into the data through various analyses:

Summary statistics for numerical and categorical columns.
Distribution analysis of key variables.
Temporal trends analysis (yearly, monthly, and by day of the week).
Correlation analysis among numerical variables.
Analysis of the top 5 crime types.

## Key Findings
VEHICLE - STOLEN was identified as the most common crime.
Certain areas and times showed higher incidences of crime.
Seasonal and day-of-week trends were observed in crime occurrences.


## Future Directions
Further analysis could involve:

Spatial analysis to identify crime hotspots.
Deeper investigation into specific types of crimes.
Predictive modeling for crime occurrence forecasting.
