# KearLaCroix_ENV872_EDA_FinalProject
Project Title: Correlation of AQI and Weather in Los Angeles County, California

Class: ENV 872/EDA

Semester: Spring 2024

# Project Members
Sarah Kear and Cole La Croix

# Overview
This GitHub repository includes historical data of Los Angeles County's daily AQI and weather patterns which were downloaded from the U.S. EPA and NOAA. The data pulled from either organization were used to determine the seasonality of daily AQI values and the correlation between AQI values and weather patterns such as temperature, average wind speed, and precipitation.

# Repository Structure
There are two folders located in this repository: Code_Output and Data.

Code_Output contains the .rmd file and the final HTML file of our project's report.

The Data folder includes three sub-folders: Processed_Data, Raw_Data, and Spatial_Data.

 1. Processed_Data includes the two CSV files. Either file contains the combined data from both the EPA and NOAA. The difference between the two is one is of the daily data and the second includes the monthly average.
 
 2. Raw_Data includes the individual 2010-2022 datasets pulled from the EPA of daily AQI values and the NOAA dataset which contains weather pattern data.
 
 3. Spatial_Data includes the U.S. shapefile from the Spatial Analysis section.

# Metadata
##### Laweather.csv
1. Column: STATION, NAME, LATITUDE, LONGITUDE, ELEVATION, DATE, AWND, FMTM, PGTM, PRCP, SNOW, SNWD, TAVG, TMAX, TMIN, WDF2, WDF5, WSF2, WSF5, WT01, WT02, WT05, WT07, WT08, WT09, WT13, WT16

2. Description: STATION: The unique identifier for the weather station, NAME: The name of the weather station, LATITUDE: The latitude coordinate of the weather station, LONGITUDE: The longitude coordinate of the weather station, ELEVATION: The elevation of the weather station above sea level (in meters), DATE: The date of the observation, AWND: Average daily wind speed (measured in meters per second), FMTM: Time of fastest mile or fastest 1-minute wind, PGTM: Time of peak gust, PRCP: Total precipitation for the day (measured in millimeters), SNOW: Snowfall amount (measured in millimeters), SNWD: Snow depth on the ground (measured in millimeters), TAVG: Average temperature for the day (degrees Celsius), TMAX: Maximum temperature for the day (degrees Celsius), TMIN: Minimum temperature for the day (degrees Celsius), WDF2: Direction of the fastest 2-minute wind (degrees from true north), WDF5: Direction of the fastest 5-minute wind (degrees from true north), WSF2: Speed of the fastest 2-minute wind (measured in meters per second), WSF5: Speed of the fastest 5-minute wind (measured in meters per second), WT01: Fog, ice fog, or freezing fog (may include heavy fog), WT02: Heavy fog or heaving freezing fog (not always distinguished from fog), WT05: Hail, snow pellets, or ice pellets, WT07: Dust, volcanic ash, blowing dust, blowing sand, or blowing obstruction, WT08: Smoke or haze, WT09: Blowing or drifting snow, WT13: Mist, WT16: Rain (measured as liquid precipitation or drizzle).


##### Ad_viz_plotval_data_2010.csv (-2023.csv)
1. Column: "Date","Source","Site ID","POC","Daily Max 8-hour Ozone Concentration", "UNITS", "DAILY_AQI_VALUE", "Site Name", "DAILY_OBS_COUNT", "PERCENT_COMPLETE", "AQS_PARAMETER_CODE", "AQS_PARAMETER_DESC", "CBSA_CODE", "CBSA_NAME", "STATE_CODE", "STATE", "COUNTY_CODE", "COUNTY", "SITE_LATITUDE", "SITE_LONGITUDE"

2. Description: Date: The specific date of observation, Source: The origin of the data, Site ID: The identifier for the monitoring site, POC: Point of Contact or specific monitor within a site, Daily Max 8-hour Ozone Concentration: The highest recorded ozone concentration over an 8-hour period, UNITS: The measurement units for the ozone concentration, DAILY_AQI_VALUE: The Air Quality Index value calculated from the ozone concentration, Site Name: The name of the monitoring site, DAILY_OBS_COUNT: The number of observations recorded that day, PERCENT_COMPLETE: The percentage of expected data actually captured, AQS_PARAMETER_CODE: The code for the specific parameter being measured according to the Air Quality System, AQS_PARAMETER_DESC: Description of the parameter being measured, CBSA_CODE: The code for the Core Based Statistical Area where the site is located, CBSA_NAME: The name of the Core Based Statistical Area, STATE_CODE: The code for the state where the site is located, STATE: The name of the state, COUNTY_CODE: The code for the county where the site is located, COUNTY: The name of the county, SITE_LATITUDE: The latitude coordinate of the site, SITE_LONGITUDE: The longitude coordinate of the site.

# Keywords
Los Angeles, California, Seasonality, AQI, meteorology, temperature, wind, precipitation

