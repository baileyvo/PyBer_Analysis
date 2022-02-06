# PyBer_Analysis
## Overview of Project

### Purpose
As a new data scientist for PyBer, a Python-based ride-sharing app, I have been asked by the CEO V. Isualize to look at the total number of rides, total number of drivers, and total fares for each city type (urban, suburban, and rural). This information was then used to generate the average fare per ride and per driver (by city type). From there, a multiple-line graph was created to show the total fares for each week by city type. 

### Resources
- Data Source: PyBer_ride_data.csv, city_data.csv, ride_data.csv (all available in the [Resources folder](https://github.com/baileyvo/PyBer_Analysis/tree/main/Resources))
- Software: Python 3.7.11, Visual Studio Code 1.63.2, Jupyter Notebook 6.4.6

## Results

### PyBer Summary by City Type
Rural, suburban, and urban city types were compared over the following categories: Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver. The results of this analysis can be seen below:

**Summary of Fare Differences by City Type**

![PyBer Summary](https://github.com/baileyvo/PyBer_Analysis/blob/main/Analysis/PyBer_Summary.PNG)

### PyBer Summary by City Type
To further compare different city types, the total weekly fares for each city type were compared for January 1, 2019 through April 29, 2019. This was done by first calculating the total weekly fares, and then creating a multiple line plot to graphically represent the information. This resulted in the graph below:

**Total Fare by City Type by Week**
![PyBer Weekly Summary](https://github.com/baileyvo/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

## Summary
Based on the analysis above, as a data scientist I have three recommendations for addressing disparities among city types:
1. The largest opportunity for growth seems to be rural cities. Efforts need to be made to increase the number of drivers in rural cities. Rural cities have the highest fare per ride and the highest fare per driver (on average).
2. There are more total drivers than total rides in urban cities. This is bringing down the average fare per driver. Efforts need to be made to ensure total drivers doe not exceed total rides.
3. Weekly fares by city type seemed to remain relatively consistent in the first four months of 2019. They did not seem to peak at the same time. It does not appear that certain weeks/dates need to be targeted as potential high-earning times where the number of drivers should be increased. 
