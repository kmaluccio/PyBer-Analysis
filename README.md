# PyBer-Analysis
Project to analyze rideshare data for Jan-May 2019 using pandas/python in Jupyter Notebook and create visualizations for the analysis using Matplotlib - also in Jupyter Notebook.

##Overview of Analysis
In this analysis, the purpose is to create a summary DataFrame with the ride sharing data by the three city types-rural, suburban, and urban. The summary will include the total rides, total drivers, and total fares for each city type. It will also include the average fare per ride and per driver. Additionally, with the given data, a multiple line graph will be created showing total weekly fares by city type. Finally, the analysis report will be based on the DataFrame and graph to determine the difference of ride sharing in each city type and how the company PyBer can use this information to make smart decisions.

## Results
The results show the average number of rides, when compared by each city type, in rural cities is about 3.5 and 2.5 times lower than urban and suburban cities, respectively. There was one outlier found in urban ride count data and the average number of rides in rural cities is about 4 and 3.5 times lower per city than the urban and suburban cities, respectively. Creating a box and whisker plot allowed us to see there are no outliers in the ride fare data, but the average fare for rides in urban cities is about $5 and $11 less per ride than the suburban and rural cities, respectively. This also showed us the average number of drivers in urban cities is four to nine times more per city than in suburban and rural cities. 

Overall, the results prove that the most drivers and the most rides happen in urban cities with the next highest in suburban cities and the lowest number of drivers and rides in rural cities. However, the average cost of rides from highest to lowest is in the reverse order: rural, suburban, urban cities. This is most likely due to the fact that in urban cities there are many shorter rides since the area is more compact with numerous restaurants/bars/shops/homes closer together compared to a suburban or rural area where shopping centers, restaurants, and homes become more spread out as you move from urban to suburban to rural cities. Therefore, we can understand why this data makes sense and the analysis allows the company to be aware of their numbers in each city type and the reason for these differences. 

From the box plots below, there is an increase in number of drivers and total fares from rural to suburban to urban cities.
![Ride Count Data](https://github.com/kmaluccio/PyBer-Analysis/blob/main/analysis/Fig2.png)
![Ride Fare Data](https://github.com/kmaluccio/PyBer-Analysis/blob/main/analysis/Fig3.png)

It is clear that the percentages of total drivers and total rides are much higher in urban cities than both suburban and rural. This can be seen in the two pie charts below.
![Percent Total Fares](https://github.com/kmaluccio/PyBer-Analysis/blob/main/analysis/Fig5.png)
![Percent Total Rides](https://github.com/kmaluccio/PyBer-Analysis/blob/main/analysis/Fig6.png)

Finally, after also calculating the average fare per ride and per driver in each city type, the total fare by city type each week from January-April 2019 can be seen in the line graph below. Comparing these numbers, it is clear that the urban cities have the most drivers, most rides, and make the most money each week. Then, the suburban cities earn about half (or less) of the total fare per week while the rural cities are the lowest in total drivers, total rides, and total fare per week.
![Fare Summary](https://github.com/kmaluccio/PyBer-Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
Based on the results, below are the business recommendations for the CEO of PyBer to address disparities among city types. Remember it is okay to have differences in each city type since there are different types of events or needs of the people in each area. The goal is to continue growing the company by having higher revenue, so higher total fares for all drivers in all cities and more rides for each driver to increase the total fare.

Recommendations based on the results:
- Reduce driver downtime for drivers in all cities by creating updates in the ride service to allow for rides to be stored in a queue based on location. So, if a driver is dropping off in one location the service can find someone close to this location to be picked up immediately after.
- To provide a better user experience, you can allow for scheduled pick ups so people can request a ride at a certain time and drivers who are working can pick up the ride. This may help get more people to use this ride share since some people may not want to wait after requesting the ride.
- Offer a special promotion or parking benefit to drivers who reach a certain number of rides per month or a certain dollar amount in fares per month. Increasing the number of rides or total fare per driver will help the company continue to grow in each city type since all drivers will be motivated to increase their total rides and/or total fares. Also, drivers could be interested in giving more rides in rural or suburban cities since one ride is, on average, 3-4 times higher than one ride in urban cities. On the other hand, if the drivers want to get more rides they may consider working in urban cities since they can higher number of rides in a period of time instead of waiting for fewer long/more expensive rides in the suburbs or rural cities. 
- Offer discounts or other incentives to rides in beginning of January or middle of February since these seem to be the times/months with the lowest total fare for every city type and offer a similar incentive for rural city rides since this may help increase the number of rides.
