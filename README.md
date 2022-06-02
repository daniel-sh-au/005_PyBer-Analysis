# Module 5: PyBer with Matplotlib

## Overview of the Analysis

### Purpose
The purpose of this assignment was to perform an analysis on the rideshare data and create a visualization displaying the total fares by city type over a span of four months. First, the Pandas library was used to create a summary for the rideshade data by city types. Then, a multiple-line chart was created using Pandas and matplotlib to display the total fares for each city type over four months. 

### Resources
* Software: Jupyter Notebook, Python 3.7.13, Pandas library, Matplotlib library
* Data Sources: [city_data.csv](https://github.com/daniel-sh-au/UofT_DataBC_Module05_PyBer-Analysis/blob/main/Resources/city_data.csv), [ride_data.csv](https://github.com/daniel-sh-au/UofT_DataBC_Module05_PyBer-Analysis/blob/main/Resources/ride_data.csv)
* Challenge Code: [Pyber_Challenge.ipynb](https://github.com/daniel-sh-au/UofT_DataBC_Module05_PyBer-Analysis/blob/main/PyBer_Challenge.ipynb)

## Results

### PyBer Summary Table

![PyBer_summary_df](https://github.com/daniel-sh-au/UofT_DataBC_Module05_PyBer-Analysis/blob/main/analysis/PyBer_summary_df.PNG)

From the PyBer summary dataframe (above), there are clear differences in the rideshare data for each city type. Urban cities have the most rides, resulting in the highest number of drivers to meet demand. This is expected as urban cities generally have the highest population of the three city types. Rural cities have the lowest amount of rides and therefore have the least amount of drivers. This correlates to population as rural cities tend to have the lowest population of the three city types. Suburban cities have a population that is between rural and suburban and as expected, the total rides and drivers for this city type are in the middle. Notably, in rural and suburban cities, there are less total drivers than total rides. However, in the urban cities, there are more total drivers then total rides. Comparing these two metrics potentially reveals an excess of drivers in urban cities. 

The total fares by city type also provides a similar trend to the total rides and total drivers metrics. As displayed in the table, urban cities have the highest total fare and rural cities have the lowest total fare. Suburban cities, similar to the previous two metrics, have their total fare in between urban and rural. The total fares metric is a direct correlation to the total rides for each city type.

When observing the average fare per ride, we can see an opposite trend to the total rides, drivers, and fares metric. Although urban cities have the highest number of total ride, this city type has the lowest average fare per ride. Additionally, rural cities have the lowest number of total rides but the highest average fare. Suburban cities are again in the middle, with their average fare per ride between urban and rural cities. This disparity can be explained by the distance the vehicle must travel in each city type. In urban cities, destinations, such as resturants, attractions, and/or necessities, are usually closer in distance than rural cities. Thus, riders in rural cities must pay a higher fare to travel further distances.

Finally, the average fare per driver has a similar trend to the average fare per ride; That is, the average fare per driver is lowest in urban cities and highest in rural cities. Suburban cities, similar to the other metrics, has its average fare per driver between the urban and rural city types. 

### PyBer Fare Summary Chart

![PyBer_fare_summary](https://github.com/daniel-sh-au/UofT_DataBC_Module05_PyBer-Analysis/blob/main/analysis/PyBer_fare_summary.png)

In the PyBer fare summary chart, it is clear that urban cities produce the highest income (fare USD) for the first four months of 2019. PyBer appears to be the busiest during the third week of February, possibly due to the US federal holiday, President's Day, being on the Monday of that week. 

## Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

From the multiple-line chart displaying the totals fares obtained for each city type from January to April 2019, it is clear that PyBer was busiest during the third week of February. This is possibly due to the President's Day being on the Monday of that week. Knowing this, the first recommendation to the CEO would be to expect a higher volume of customers during this week and to plan accordingly with an appropriate amount of drivers. Additionally, ridership appears to be higher in the spring months (March and April) than in the winter months (January and February). To promote ridership durng the winter months, the CEO could provide a discount or incentive for riders. This can make it more attractive to use PyBer during those winter months. Finally, the PyBer Summary Table reveals that there is an excess of urban drivers. The third recommendation to the CEO would be to reduce the number of drivers in urban areas. Although urban cities have a higher demand for drivers, the total driver count for urban areas (2,405) is significantly larger than the total rides (1,625). Therfore, some of the drivers can be removed to save cost. 
