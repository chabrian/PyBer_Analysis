# PyBer_Analysis

## Overview of PyBer Analysis

In this project, I have been tasked with analyzing data for PyBer, a ride-sharing app company, to determine performance characteristics related to driver availability and customer fares. I collaborated directly with PyBer to analyze, report, and present financial and performance metrics for rural, urban, and suburban city types. PyBer has given me the following tasks to complete the analysis:

1. Create a visualization of the average fare vs. the total number of rides per city.
2. Create a visualization of the number of rides for each city type.
3. Create a visualization of the fares for each city type.
4. Create a visualization of the number of drivers for each city type.
5. Determine the percentage of total fares by city type.
6. Determine the percentage of total rides by city type.
7. Determine the percentage of total drivers by city type.
8. Present a table of the total rides, total drivers, total fares, average fare per ride, and average fare per driver for each city type.
9. Create a multiple-line chart for the total weekly fare by city type from January through April 2019

PyBer has provided two datasets with ride-sharing information in CSV files. The city_data.csv file contains a list of cities, driver counts, and city types. The ride_data.csv file contains a list of ride ID, city, date, and fare in $USD. I used Jupyter Notebook in a Python3 environment and imported the pandas and matplotlib modules to create dataframes and charts for data visualization. The full set of resources and PyBer analysis results are shown below.

## Resources
- Data Source: ride_data.csv, city_data.csv
- Software: Python 3.8.9, Jupyter Notebook

## PyBer Results

Figures 1 through 7 provide visualizations of the PyBer datasets that distinguish the performance of the ride-sharing applicaton in rural, urban, and suburban city types.

- Average Fare vs. Total Number of Rides per city

<div align="center">

|![Fig1](https://user-images.githubusercontent.com/95327115/150699704-4d2886f6-4188-4ae0-8fd4-c196b9789cdb.png)|
|:--:|
|*Figure 1*|

</div>
  
- Number of Rides, Fares, and Number of Drivers for each city type

<div align="center">

|*Figure 2*|![Fig2](https://user-images.githubusercontent.com/95327115/150699892-5302a2e8-28c0-4c84-a8bc-0f42e957231a.png)|
|:--:|:--:|
|*Figure 3*|![Fig3](https://user-images.githubusercontent.com/95327115/150699901-fbe9060d-4df1-4116-80f8-05a71e047c7e.png)|
|*Figure 4*|![Fig4](https://user-images.githubusercontent.com/95327115/150699911-ef520930-582c-411b-95da-255c39f93acc.png)|

</div>

- Total Fare, Total Ride, and Total Driver percentage for each city type

<div align="center">

|*Figure 5*|![Fig5](https://user-images.githubusercontent.com/95327115/150700111-6fae0dca-d669-4f0e-85ce-fce885297545.png)|
|:--:|:--:|
|*Figure 6*|![Fig6](https://user-images.githubusercontent.com/95327115/150700119-287516a5-b6d5-41d3-8ae3-9e778761585c.png)|
|*Figure 7*|![Fig7](https://user-images.githubusercontent.com/95327115/150700128-b1a45787-e48e-4312-a843-f7a24785d636.png)|

</div>

Figure 8 below provides a summary breakdown of the total rides, total drivers, total fares, average fare per ride, and average fare per driver for each city type.

- PyBer Summary by City Type

<div align="center">

|<img width="600" alt="PyBer_city_type_summary" src="https://user-images.githubusercontent.com/95327115/150700176-8b5b1f3f-920b-4f6b-bd20-65d88510e748.png">|
|:--:|
|*Figure 8*|

</div>

In the figure above, the urban city type has the highest number of rides and drivers and the lowest average fare per ride and per driver.  On the contrary, the rural city type has the lowest number of rides and drivers and the highest average fare per ride and per driver. The suburban city type sits in between the rural and urban categories across all metrics. 

Figure 9 depicts the total weekly fare from January to May 2019 for each city type.

- PyBer Total Weekly Fares by City Type

<div align="center">

|![PyBer_fare_summary](https://user-images.githubusercontent.com/95327115/150700206-108482b8-0337-4ed5-8f16-a3d72553f45c.png)|
|:--:|
|*Figure 9*|

</div>

The above figure shows the total weekly fare is greatest for urban cities type followed by suburban and then rural city type on a consistent basis. The weekly total fares has some fluctuation over the period shown, but is mostly consistent at around $250/week for rural, $1,000/week for suburban, and $2,200/week for urban.

## PyBer Summary

The results of this analysis give evidence to the disparity of available drivers and cost of fares between rural, urban, and suburban city types. Based on the provided figures and analysis, I recommend the following three business ideas to the PyBer CEO to create more equality for PyBer users:
1. Decrease ride fares in rural cities. Although this would seemingly decrease the total revenue for rural cities, this measure could encourage more users to choose PyBer over other methods of transportation. This would effectively decrease the average fare.
2. Offer more promotions in rural and surburban areas. Similar to the first recommendation, promotions would decrease total revenue for rural and suburban cities, but it could encourage more users to choose PyBer, effectively increasing the total rides and decreasing the overall average fare.
3. Increase ride fares in urban areas. This measure would increase the total revenue for urban cities to decrease the disparity between rural, urban and suburban city types. The drawback of this recommendation is that the total number of rides could decrease if fare prices were to increase as users may choose alternate transportation methods. 
