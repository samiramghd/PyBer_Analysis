# PyBer_Analysis
PyBer, ride-sharing app analysis

### Overview of the analysis: Explain the purpose of the new analysis.

In this challenge we create a summary DataFrame of the ride-sharing data by city type and visualizing the rideshare data for PyBer to help improve access to ride-sharing services. and Then, using Pandas and Matplotlib to create a multiple-line graph that shows the total weekly fares for each city type.

### Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

In Deliverable 1 we have to make these steps ready

- total rides for each city type
- total drivers for each city type
- total amount of fares for each city type
- the average fare per ride for each city type.
- the average fare per driver for each city type. 
- then, Create a PyBer summary DataFrame.
which the results are shown in this picture.

![This is an image](https://github.com/samiramghd/PyBer_Analysis/blob/main/analysis/del1.PNG)

In Deliverable 2 we need to create a multiple-line graph that shows the total fares for each week by city type.

- create a new DataFrame showing the sum of the fares for each date where the indices are the city type and date.
- Create a pivot table
- Set the "date" index to datetime datatype.
- Create a new DataFrame using the "resample()" function
- Using the object-oriented interface method, plot the resample DataFrame
which our multiple-line chart looks like the following image

![This is an image](https://github.com/samiramghd/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

> when we compare DataFrame and chart we can realize that total fare in Urban is higher than Suburban and Rural. Total drivers in Urban is more than total rides and for Suburban and Ruraltotal rides are more than total drivers. Average fare per driver and ride in Rural is more than other two what I'm thinking maybe it's better to spread out the drivers and fares that way it would be better and easier to choose where to work.

### Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

Based on the same PyBer_fare_summary picture and the results we got in this module

1. the Urban cities has the highest fare and gives good opportunities to expand rides with higher fare.

2. Based on total drivers we might have some opportunities in Rural and Suburban, since we have less drivers there and if we had some more information about distances it could be helpful to realize if we need more drivers.

3. By coparing total drivers and total rides we realize we have more drivers in Urban than rides which make us think there might not be enough rides for all drivers and it's better if they spead out all over.

