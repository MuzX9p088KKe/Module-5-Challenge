# Module-5-Challenge: Rideshare Data Analysis


## Overview of the analysis:

The purpose of this project was to use the data of many rides gathered from a rideshare company and to put together a table to visualize the data organized by city type. The cities were assigned one of three types: rural, suburban, or urban.

After the data had been re-organized, we were also tasked to use this dataframe create a multiple-line graph to help identify meaningful trends.


## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

Several obvious trends appear when looking at the data we were provided. 

First of all, the total amount of rides is not at all evenly distributed between each type of city. Rural cities have a total of 125 rides, suburban cities have 625, and urban cities have 1,625. This means that the ride count of urban cities is larger than twice the other two types combined. This is quite a large discrepancy.

In terms of the amount of drivers, we see a continuation of the trend observed above. Rural cities have a total of 78 drivers, suburban cities have 490, and urban cities have 2,405. The difference between the total amount of drivers of the urban cities is even more pronounced for this metric as it is a little under less than five time higher than the other two categories combined.

Analyzing the fares is where this dataset delivers some really interesting insight. While, obviously, the total amount of fares mirror the general trends observed in the previous metrics, it does while staying much closer between city types. Rural cities have a total of 4,237.93 USD, suburban cities are at 19,356.33 USD, and urban cities at 39,854.38 USD. These amounts are indeed much closer than the other metrics.

Upon closer inspection, this can be explained by the fact that the average fare per ride is highest in rural cities at 34.62 USD, followed by suburban cities at 30.07 USD, and finally urban cities at 24.53 USD. 

Lastly, this had some consequences for the fare per driver also. Indeed, the average fare trends across city types described above trend opposite to the amount of drivers. This caused average fare per drivers to be highest in rural cities at 55.49 USD, followed by suburban cities at 39.50 USD, and finally urban cities at 16.57 USD. 


## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

After looking through all major trends for the dataset, the following observations can be made:

As the city size grows between rural to urban, so does the popularity of the app as demonstrated through total rides and drivers. At the same time, while total revenue also trends up with city, it does so at a disproportionately lower rate. 

While there are over twice as many rides in urban cities, the total fares do not show that same rate of increase. This could be due to the fact that there are more drivers competing for the same customers and also due to the fact that competitors app are likely present in more urban areas, keeping revenues more competitive. This would be something to monitor as lower prices on another app could convince users to switch to competitors.

As price per ride was trending opposite to ride amounts in less urban cities, it may be worth looking into developing the suburban and rural cities market. This could be achieved not only by marketing to potential users to increase demand, but also to prospective drivers to meet demand.

It makes sense that urban cities see the most demand for ridesharing among all three types, causing both the amount of users and riders to be highest in that type of market. Tweaking the algorithm for the fare amount depending on the overall demand at a certain type may help increase fares during rush hour to keep satisfaction among drivers a bit higher. This measure would likely not make as much sense in rural cities where average fares are already higher than in the other city types.


