# PyBer_Analysis

  ## Resources
  - Data Sources:  city_data.csv, ride_data.csv
  - Software:  Anaconda 4.9.2, Jupyter Notebook 6.0.3 , Python 3.7.6 
  - Using:  Pandas, NumPy
  
## Overview of the analysis:

A rideshare company, PyBer, was interested in conducting analysis on city and ride data held by the business to better understand ride-sharing by city type.  Using Python skills and knowledge of Pandas, we created a summary DataFrame of the ride-sharing data by city type.  Then, using Pandas and Matplotlib, we created a multiple-line graph that shows the total weekly fares for each city type.  This data visualization of the results helped the CEO of PyBer to understand week-to-week trends for fares by city type (Urban, Suburban, Rural), specifically for rides occuring during the range of weeks from January 1st, 2019 to April 29th, 2029.

This summary report will summarize how the data differed by city type and how those differences can be used by the decision-makers at PyBer.


## Purpose of the analysis

The main purpose of this further analysis is to visualize weekly trends for fare data by city type (Urban, Suburban, Rural) across a set time period, January 1st 2019 to April 29th, 2029.  The visualization of the data will help make the findings more digestable for stakeholders.  We will also advise on how the differences in data can be used by decision-makers at PyBer to maximize business performance.

## Results:

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)

Through our analysis we were able to ascertain the following

### Total Rides

Rural        125
Suburban     625
Urban       1625

Logically the highest number of rides taken was in Urban cities.  The number of rides taken in Urban cities was significantly higher than in both Suburban and Rural cities.  This is likely due to population size differences between Urban, Suburban and Rural cities.  Demand is higher in terms of volume of rides in Urban cities.

Suburban had 38% the amount of rides that Urban had.
Rural had 8% the number of rides that Urban had.

### Total Drivers

Rural         78
Suburban     490
Urban       2405


There are more drivers in Urban cities than there are in Suburban or Rural which is logical based on the higher demand for rides in Urban cities.  What is less logical is that there are more drivers in Ubran cities than there are rides taken.

Suburban cities have 20% the number of drivers that Urban cities have.  This is despite Suburban cities having 38% of the number of rides that Urban cities had.  
Rural cities have 3% the number of drivers that Urban cities have.  Rural cities have 8% of the rides Urban cities have.

Supply and demand are not proportional across the 3 city types.

### Total Fares

Rural        $4,327.93
Suburban    $19,356.33
Urban       $39,854.38

Urban cities had significantly higher total fares than Suburban or Rural cities.

Suburban cities have 49% of the total fares that Urban cities have.  Despite this Suburban cities only have 20% of the number of drivers that Urban cities have.  
Rural cities have 11% of the total fares that Urban cities have  Despite this Rural cities only have 3% of the number of drivers that Urban cities have.

One hypothesis to explore is, provided fare/ mile is the same across all city types, Suburban and Rural passengers may travel greater distances given locations are not as condensed as they are in the Urban cities.  We explore this further when we look at average fares per ride.

## Average Fare Per Ride

Rural       $34.62
Suburban    $30.97
Urban       $24.53

As hypothesized when exploring total fares, the Average Fare Per Ride is highest for Rural passengers and Suburban passengers as they typically must travel great distances than Urban city passengers to reach their destinations.



There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)
