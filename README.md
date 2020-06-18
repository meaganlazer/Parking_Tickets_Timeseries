# Alternate Side Parking Tickets in NYC

## Overview<br/>
As a car owner in NYC who has spent innumerable hours on the dance of alternate side parking, I set out to analyze parking ticket patterns and to determine if there are variables present to predict whether or not one is more likely to get a parking ticket. I obtained over 7M individual ticket rows from the NYC Open Data API for analysis. I used Python to upload, clean, and reshape data. I then included geospatial shape files to identify hotspots, organized by precinct, for alternate side parking tickets. Finally, I merged NOAA weather data into the Pandas Dataframe to evaluate the impact of exogenous variables. Model uses location and weather patterns that more likely result in tickets with a focus on alternate side parking violations.

----
## Ticket Count by Weekday, by Precinct
![](Images/Weekday.gif)<!-- .element height="50%" width="50%" -->

## SARIMA
Used SARIMA Machine Learning to predict daily ticket issuance.

<img src="Images/SARIMApng.png" width ="700">

## Tools<br/>
- API
- Python
- Geopandas
- SARIMA

**Data Sources:**
1. NYC Open Data: [Open Parking and Camera Violations](https://data.cityofnewyork.us/City-Government/Open-Parking-and-Camera-Violations/nc67-uf89)
2. NYC Open Data: [Police Precincts](https://data.cityofnewyork.us/Public-Safety/Police-Precincts/78dh-3ptz)
3. NOAA [National Centers for Environmental Information](https://www.ncdc.noaa.gov/cdo-web/search)
