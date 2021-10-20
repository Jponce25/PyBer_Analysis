# PyBer_Analysis

## Overview

The objective of this analysis is to get the relationships between the type of cities the numbers of drivers and riders, as well as the porcentage of fare for a ride-sharing app company. We have two data sets: the ride_data.csv with information of the fares from January to May of 2019 and the city_data.csv that has a column with the type of city and the number of drivers. 

In order to make the complete summary of the information we have to merge both databases. From the merged database we can calculate the Total Rides, Total Drivers, Total Fares, the Average Fare per Ride and the AverageFare per Driver for each type of city. Finally, we use the merged database to get a multiple-line graph to visualize the total weekly fares for each city type. This analysis will help improve access to shared transportation services and determine affordability for underserved neighborhoods.

## PyBer_Analysis Results

![](https://github.com/Jponce25/Election_Analysis/blob/1abab17e1a8a015fe71b7d77a430fa9cda1658b6/Resources/Imagen3.png)

Urban cities are the ones with the most drivers and trips during the analyzed period, they are also logically the ones with the most fare in absolute terms. On the other hand, the type of city with the lowest number of trips, drivers and fares are rural areas. This sounds logical due to the population density of each type of city, however, doing a relative analysis of the data, that is, calculating averages, another reality can be observed.

The average fare per ride changes trend, and now it is rural areas that have the highest average ($34.62), the same happens with the average fare per driver that is higher in rural-type cities with $55.49. For urban areas, it is observed that the average fare per ride and the average fare per driver is the lowest, with $24.53 and $16.57, respectively.

![](https://github.com/Jponce25/Election_Analysis/blob/1abab17e1a8a015fe71b7d77a430fa9cda1658b6/Resources/Imagen3.png)

In the multiple line graph that we created, we can observe the historical behavior of the rates for each of the types of city. As already identified in the summary, it is urban areas that have the highest rates and rural areas that have the lowest.

During the third week of February, there is a growing trend in rates for all types of city, which could be due to a greater number of rides for that date or an increase in rates (perhaps for longer rides). To check these hypotheses we graph also the data of number of rides where we can observe an increase in the number of rides in the third week of February, that is, there is evidence that the two series (total rides and fares) are related.

![](https://github.com/Jponce25/Election_Analysis/blob/1abab17e1a8a015fe71b7d77a430fa9cda1658b6/Resources/Imagen3.png)

## PyBer_Analysis Summary

After analyzing the results, the recommendations observed for the company are the following:

- Although urban cities are the ones with the highest total rates, there is a saturation of drivers with respect to the number of rides, therefore, despite representing the majority of income, an additional investment could generate few benefits. It would be necessary to complement the analysis with a study of the amount of demand for the service.

- Regarding rural cities, it is where there is the greatest investment opportunity because the number of drivers does not exceed the number of rides. The average fare per driver is also the highest, which shows an opportunity to add a greater number of drivers, it is important to consider that in rural areas the distance of the routes is greater and probably thats the reason what increases the total number of fares.

- Finally, by analyzing the temporal evolution of our data, we can identify dates where a greater number of trips could be promoted for specific areas, for example for the third week to suburban areas.

