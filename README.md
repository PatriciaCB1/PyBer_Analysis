# PyBer_Analysis

  ## Resources
  - Data Sources:  city_data.csv, ride_data.csv
  - Software:  Anaconda 4.9.2, Jupyter Notebook 6.0.3 , Python 3.7.6 
  - Using:  Pandas, Matplotlib
  
## Overview of the analysis:

A ride-share company, PyBer, was interested in conducting analysis on ride data held by the business by city type (Urban, Suburban, Rural) to better understand metrics such as total rides, number of drivers, total fares, average fares and average fare per driver by city type.  Using Python skills and knowledge of Pandas, we created a summary DataFrame of the ride-sharing data by city type.  Then, using Pandas and Matplotlib, we created a multiple-line graph that shows the total weekly fares for each city type.  This data visualization of the results helped the CEO of PyBer to understand week-to-week trends for fares by city type (Urban, Suburban, Rural), specifically for rides occuring during the range of weeks from January 1st, 2019 to April 29th, 2029.

This summary report will detail how the data differed by city type and how those differences can be used by decision-makers at PyBer to support optimal business and passenger outcomes.


## Purpose of the analysis

The main purpose of this further analysis is to understand, quantify and visualize trends for fare data by city type (Urban, Suburban, Rural) across a set time period, January 1st 2019 to April 29th, 2029.  The visualization of the data will help make the findings more accessible for stakeholders.  We will also advise on how the differences in data can be used by decision-makers at PyBer to maximize business performance.

## Results:

Through our analysis we were able to ascertain the following:

### Total Rides By City Type

- Rural:     125
- Suburban:  625
- Urban:    1625

As would seem intuitive, the highest number of rides taken was in Urban cities.  The number of rides taken in Urban cities was significantly higher than in both Suburban and Rural cities.  This is likely due to population size differences between Urban, Suburban and Rural cities.  It is logical to hypothesize that demand is higher in terms of volume of rides in Urban cities.

Suburban cities had 38% the number of rides that Urban cities had.
Rural cities had 8% the number of rides that Urban cities had.

### Total Drivers By City Type

- Rural:      78
- Suburban:  490
- Urban:     2405


There are more drivers in Urban cities than there are in Suburban or Rural, which is logical based on the higher demand for rides in Urban cities.  What is less logical is that there are more drivers in Urban cities than there are rides taken.

Suburban cities had 20% the number of drivers that Urban cities had.  This is despite Suburban cities had 38% of the number of rides that Urban cities had.  
Rural cities had 3% the number of drivers that Urban cities had.  Rural cities had 8% of the rides Urban cities had.

Supply and demand are not proportional across the 3 city types.

### Total Fares By City Type

- Rural:        $4,327.93
- Suburban:    $19,356.33
- Urban:       $39,854.38

When we look at the Total Fares by City Type, Urban cities had significantly higher total fares than Suburban or Rural cities.

Suburban cities had 49% of the total fares that Urban cities had.  Despite this Suburban cities only had 20% of the number of drivers that Urban cities had.  
Rural cities had 11% of the total fares that Urban cities had.  Despite this Rural cities only had 3% of the number of drivers that Urban cities had.

One hypothesis to explore is, provided fare/ mile is the same across all city types, Suburban and Rural passengers may travel greater distances given locations are not as condensed as they are in the Urban cities.  We explore this further when we look at average fares per ride.

### Average Fare Per Ride

- Rural:       $34.62
- Suburban:    $30.97
- Urban:       $24.53

As hypothesized when exploring total fares, the Average Fare Per Ride is highest for Rural passengers and Suburban passengers as they typically travel greater distances than Urban city passengers to reach their destinations.

### Average Fare Per Driver

- Rural:       $55.49
- Suburban:    $39.50
- Urban:       $16.57

Not surprisngly the average fare per driver was highest in Rural cities, followed by Suburban cities with Urban cities seeing the lowest fare per driver.  In further analysis it would be interesting, if we had access to driver ID data associated with each ride, to analyze the total fares per driver.

To view these conclusions collectively, please refer to the following summary DataFrame.

![City_Type_Summary_DF](https://github.com/PatriciaCB1/PyBer_Analysis/blob/main/City_Type_Summary_DataFrame.png)





The following chart displays the difference in total fares by city type for Urban, Suburban and Rural cities for the specified period. This is a visual representation of our findings from Total Fares By City Type as detailed above.

![Total_Fares_By Week_By_City_Type](https://github.com/PatriciaCB1/PyBer_Analysis/blob/main/Analysis/Pyber_fare_summary.png)

This line chart shows us the following:
- In the months spanning January 1st through April 29th across the specified years, Total Fares for Urban and Suburban cities were highest at the start of the last week of February.  The start of the last week of February was the second highest in terms of Total Fares for Rural cities (clearly a good week for PyBer for all city types.
- Rural cities' highest Total Fares was at the very start of April
- For Urban and Suburban cities the first week of January saw the lowest total fares.  For Rural cities the lowest Total Fares occured mid March.
- The difference by week are quite significant as some weeks see double the number of Total Fares by city type than others.
- The combined line chart displays the higher level Total Fares overall for Urban, followed by Suburban then Rural.


## Recommendations to the CEO

Research provides answers, however it often turns up more questions and further areas for exploration.  Based on our observations in this analysis, we would make the following recommendations to PyBer:

  - Reduce the number of Urban city drivers as in our analysis we found that there were more drivers than there were rides, meaning some riders did not have any passengers at all.
  - Potentially increase the number of drivers for Rural and Suburban cites.  This would require further analysis as we would want to exclude drivers that did not have any passengers from the data to find the correct proportions.  We might want to create a new column in our data for "Active Drivers" when we conduct the analysis to remove any drivers that had no passengers.
  - Average fares are significantly higher in Rural cities.  If Pyber is currently applying the same cost per mile rate for all city types, the business may gain additional revenues and increase average fares for Urban cities by increasing the rate in Urban cities.
  - Conduct further analysis on distance average distanced traveled by passengers across the city types to potentially support a distance-based tiered pricing structure.
  - Conduct further research to understand the above metrics and their relationship to population size across the 3 city types.  Also conduct primary research to understand how travel/ commute behaviors, usage, awareness and attitudes differ across the city types to better understand the potential addressable market for each city type and how best to maximize profitability and passenger satisfaction across all 3 types.  
  - Conduct further research (desk and primary) to understand why Total Fares are nearly double for some weeks than they are for others.  Box & Whisker plot visualizations of our existing research may help us to better understand if there are outlier fares or numbers of trips causing this variation before we undertake additional research.
  - Review data validity/ integrity and potentially do data cleaning as the years 2021 - 2029 have not yet occured.
