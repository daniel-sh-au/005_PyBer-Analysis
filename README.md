# Module 5: PyBer with Matplotlib

## Overview of the Analysis

### Purpose
The purpose of this assignment was to perform an analysis on the rideshare data and create a visualization displaying the total fares by city type over a span of four months. First, the Pandas library was used to create a summary for the rideshade data by city types. Then, a multi-line chart was created using Pandas and matplotlib to display the total fares for each city type over four months. 

### Resources
* Software: Jupyter Notebook, Python 3.7.13, Pandas library, Matplotlib library
* Data Sources: [city_data.csv](https://github.com/daniel-sh-au/UofT_DataBC_Module05_PyBer-Analysis/blob/main/Resources/city_data.csv), [ride_data.csv](https://github.com/daniel-sh-au/UofT_DataBC_Module05_PyBer-Analysis/blob/main/Resources/ride_data.csv)
* Challenge Code: [Pyber_Challenge.ipynb](https://github.com/daniel-sh-au/UofT_DataBC_Module05_PyBer-Analysis/blob/main/PyBer_Challenge.ipynb)

## Results
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)

![PyBer_summary_df](https://github.com/daniel-sh-au/UofT_DataBC_Module05_PyBer-Analysis/blob/main/analysis/PyBer_summary_df.PNG)

From the PyBer summary dataframe (above), there are clear differences in the rideshare data for each city type. Urban cities have the most rides, resulting in the highest number of drivers to meet demand. This is expected as urban cities generally have the highest population of the three city types. Rural cities have the lowest amount of rides and therefore have the least amount of drivers. This correlates to population as rural cities tend to have the lowest population of the three city types. Suburban cities have a population that is between rural and suburban and as expected, the total rides and drivers for this city type are in the middle. 

The total fares by city type also provides a similar trend to the total rides and total drivers metrics. As displayed in the table, urban cities have the highest total fare and rural cities have the lowest total fare. Suburban cities, similar to the previous two metrics, have their total fare in between urban and rural. The total fares metric is a direct correlation to the total rides for each city type.

When observing the average fare per ride, we can see an opposite trend to the total rides, drivers, and fares metric. Although urban cities have the highest number of total ride, this city type has the lowest average fare per ride. Additionally, rural cities have the lowest number of total rides but the highest average fare. Suburban cities are again in the middle, with their average fare per ride between urban and rural cities. This disparity can be explained by the distance the vehicle must travel in each city type. In urban cities, destinations, such as resturants, attractions, and/or necessities, are usually closer in distance than rural cities. Thus, riders in rural cities must pay a higher fare to travel further distances.

supply low, price up

![PyBer_fare_summary](https://github.com/daniel-sh-au/UofT_DataBC_Module05_PyBer-Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)
