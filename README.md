# PyBer_Challenge
Module 5 Challenge
# Analysis of Weekly Fares by City Type
## Overview of the Analysis
An analysis was completed to review the weekly fares by city type. In order to complete this analysis, we merged two dataframes to create a new dataframe. The data frame included the following elements: city, date, fare, ride id, driver count, and type. The Analysis will leverage the fields of date, fare, and type to provide a summary of the weekly fares by ciry type. 

## Results of the Analysis
Before completing the final analysis, we reviewed the data to obtain an understanding of our data set. Below is a summary of the data by city type. 
- Rural  
  - Total Rides: 125
  - Total Drivers: 78
  - Total Fares: $4,327.93
  - Average Fare per Ride: $34.62
  - Average Fare per Driver: $55.49
- Suburban
  - Total Rides: 625 
  - Total Drivers: 490
  - Total Fares: $19,356.33
  - Average Fare per Ride: $30.97
  - Average Fare per Driver: $39.50
- Urban
  - Total Rides: 1,625
  - Total Drivers: 2,405
  - Total Fares: $39,854.38
  - Average Fare per Ride: $24.53
  - Average Fare per Driver: $16.57

Below is a summary table of the items listed above. 
![Summary Table](https://github.com/codfjenn/PyBer_Challenge/blob/main/Summary%20of%20PyBer_Data.png)

After reviewing the individual city types we compiled the total weekly fares by type for the period of January 2019 - April 2019. The visual below confirms that the urban market generates significantly more fares than the other mareket throughout the entire period reviewed. The total fares volume does not have any week at a city type level that is an outlier that could potentially skew the data. 
![Summary Weekly Fares by City Type](https://github.com/codfjenn/PyBer_Challenge/blob/main/PyBer_fare_summary.png)

## Reccommendations 
Based on the Analysis performed, I have included three recommendations to address disparities among the city types: 
- The total fares amount should always be the highest where we have the highest volume of drivers. The urban city type is the largest fare total; however, the average fare per driver is the lowest. Therefore, we have many drivers that are not completing a large volume of rides. We should offer incentives to encourage drivers to complete more fares. 
- The drivers in the Urban market should be reviewed for inactivity as the summary statistics list there are more drivers than rides performed. We should take this analysis a step further and remove the drivers from the dataset that are not active. The total drivers being greater than the total rides is scewing this datasets average fare per ride. A more indpth review should be completed and we should consider removing drivers that are not active. 
- The Rural city type has the highest per fare ride and the highest per driver. We should pull in additional data to confirm the duration and distance of these rides. With the lowest volume of drivers the average fare per driver is appropriately in the rural city type; however, we shoud obtain a better understanding of the rides being completed. 
