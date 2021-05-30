# PyBer_Analysis

## Background  
The initial project was to perform exploratory analysis on ride sharing data from csv files for PyBer app. As part of the analysis, several types of visualizations were created (such as by city type, drivers, riders, fares) using Panda scripts, libraries and jupyter notebook. The purpose of the analysis and visualizations were to help Pyber improve their operations such as access to ride sharing services and affordability.

<br />

## Scope
The scope of the project is a new assignment where Pyber requires a summary of ride sharing data by city type. The goal is to create a multiple line chart that will show total weekly fares by city.
<br />

## Resources
- Data Source: 
    - Resources\city_data.csv
    - Resources\ride_data.csv
- Code file: PyBer_Challenge.ipynb
- Images:
    - analysis\PyBer_fare_summary.png

<br />

##  Results
From the summary stats below, we can infer the following:
- Urban cities have the highest ride count, almost 68%, with suburban at 26% and rural cities at 5 %.
<br />

- Urban cities have more drivers than riders which results in:
    -  Lower average fare per drivers, whereas Suburban and rural cities have more demand for ride sharing but not enough drivers available.
    - Low affordability on suburban and rural areas.
<br />

- Total Fare by city by week  - looking at multi line chart, we can deduce that urban cities generate the highest revenue with ease of access and affordibility:
	- Urban cities generate over $2000 most weeks with a few exceptions.
	- Suburban cities average city fare stays close to 1000 for the most part, approx. 50 % less than urban
    - Rural cities weekly fare stays under 500 with one peak hitting 500 in the beginning of April, at least 75% less than urban cities
<br />
<br />

Summary Stats:
<img src="analysis\Summary.png" width=700 align=center>

<br />
<br />


Multi Line Chart:
<img src="analysis\PyBer_fare_summary.png" width=700 align=center>

<br />
<br />


##  Summary

Based on the results above, the following measures can be taken to improve affordibility, make ride sharing accessible to under served areas and generate more revenue:
1)  Suburban and rural area in specfic will benefit from an increase in driver count. It will provide ease of access to these under served areas.
2) To make ride sharing afforable and to generate more revenue in rural and suburban cities, fare discounts can encourage higher rider count.
3) We see that urban cities have more supple (drivers) than demand (riders). Allowing loyalty or rewards programs can encourage more people to use ride sharing app in urban cities which can help close the disparity between driver and rider count.
