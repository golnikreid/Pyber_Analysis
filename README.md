


# Pyber Analysis

  

## Overview of the Analysis

  

### Purpose
The purpose of this analysis is to create a summary DataFrame of the ride-sharing data by city type. Then create a multi-line graph depicting the total weekly fares for each city type. Finally, draw conclusions from this info so that Pyber can make informed decisions.

  

## Results
The analysis of PyBer data involved grouping the data by the city type (Rural, Suburban, and Urban). From there, the total rides, drivers and fares are summed up. With those, we can find the average fare per ride and average fare per driver as seen in the chart below:

![Summary](Resources/SummaryDataFrame.png)

From the table, we can see that Average Fare per Ride and per Driver is highest in rural cities and lowest in urban cities.

To switch gears and analyze the fare overtime based on city type we go back to the original data. and group it by type then date. Next create a pivot table and plot it. The graph can be seen below:

![PyBer Fare Summary](Resources/PyBer_fare_summary.png)

  
As can be seen from the graph, the total fare over this time period is always highest in urban cities and always lowest in rural cities.

## Summary
Based on the Results, we can see that while the highest average fare per driver and per ride is highest in rural cities and lowest in urban cities, the total fare is the inverse. There are a few options the CEO can take to correct the disparity between the city types.

 First, they could run a promotion to increase or decrease the number of drivers to adjust the average fare per driver. Average Fare per Driver and Total Drivers share an inverse relationship (i.e if one decreases the other increases and vice versa) so adjusting the total drivers in a city type can adjust the disparity. Second, they can adjust the Total Rides in a city type. Similar to before, Average Fare per Ride and Total Rides share an inverse relationship so an increase or decrease to Total Rides can correct disparities. Finally, increasing the Total Fares in a given city type would would increase both the Average Fare per Ride and per Driver since it has a direct relationship with Total Fares. 
