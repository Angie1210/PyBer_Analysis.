# PyBer_Analysis.

## Overview of the analysis:
The purpose of this project is to analyze the ride-sharing company, Pyber. We will performe an exploratory analysis to determine relationships between variables in order to find their opportunity areas and help them to improve their services. We will use Python and Pandas to clean and organize the data and Matplot to create charts for visualize our findings. Our  goal is to create a summary DataFrame of the ride-sharing data by city type and create a multi linear graph that shows the fares by week in each city type.

## Results:
### Ride Sharing Data by city type.

We reorganized the data by using the groupby() function to get a summary dataframe that displays all the information per city type, so now we can compare the performance of the ride sharing service in each city type. As a result, we can see that the highest average fares are in the Rural areas and that the Urban type is the one with more demand of rides but also a lot of drivers, actually it has more drivers than rides, so it affects the average fare per driver. Also the average fare per ride is the lowest one in the Urban type. 

![Screen Shot 2022-03-25 at 10 45 35 PM](https://user-images.githubusercontent.com/43548929/160226656-8afde2a3-3ec8-4af9-b8a0-faee7ff377c0.png)

### Total Fares by city type.

We created a pivot table to display the total fares per city type in a period of time. As expected the total fare amount is aprox 4x higher than the rural total fares. The three of them are kinf of constants except in April that we can see a huge drop on April, it's really big so we need to double check that the information in the database is accurate.

![Screen Shot 2022-03-25 at 11 38 14 PM](https://user-images.githubusercontent.com/43548929/160228722-a1f76741-95cc-4c1e-92ff-c04c1c0b361f.png)


## Summary:
Our business recommendations are:
* Reduce the number of drivers in Urban areas, so each driver can have more opportunities to get a ride and make more money in average. 
* Relocate some drivers to Rural areas, maybe there is more demand and not enough drivers to faced it and that's why their average fare per driver is so high.
* Increase your fares in Urban areas, because there are around 12x more rides than in rual areas, but the total fares dont have the same proportion. So increasing prices is another option to increase fare per ride and per drivers in Urban type.
* Check your April information or analyse the resason for such a big drop in the rides.
