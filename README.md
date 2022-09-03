# PyBer_Analysis
## Overview of the Analysis
   * The purpose of the new analysis is to create a multiple-line graph that shows the total weekly fares for each city type.
###   The Analysis entails
       * Creating a DataFrame using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare          amount for each date and time. 
       * Another DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare." 
       * A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28. 
       * A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
       * Finally an annotated chart was created showing the total fares by city type and saved to the "analysis" folder.
#### Results
       * Total Rides by city type: Urban city type has the most rides(1,625), 13 times the total ride of the Rural city type which has least number of rides(125) 
         The Suburban city type has 625 rides, 5 times the number of ride for the Rural city .
         
       * Total Drivers by city type: Urban city type has the most drivers with 2,405,about 31 times the total drivers of the Rural city type 
         which has the least number of total drivers by city type of 78 drivers,the total drivers of the suburban city type is 490 drivers, 
         a 6.3 times the Rural city type`s total drivers value.
         
       * Total Fare by city type : Urban city fare constitute 62,73% of total fare for PyBer($39,854.38) The Suburban city type provided 30.46% of 
         the total Fare for PyBer ($19,356.33).The Rural city fare constitute 6.81% of the total fare for Pyber ($4,327.93)
         
       * Average Fare Per Ride by city type: Here Rural city type actually have the highest average fare per ride of $34.62,
         followed by the Suburban city type`s average fare per ride of $30.97 and the Urban city type has the Average fare per ride of $24.53
         
       * Average Fare Per Driver by city type: Here the Rural city type again have the highest average fare per driver of $55.49,followed by 
         the Suburban city type's average fare per Driver of $39.50 and the Urban city has the Average fare per driver of $16.57
      
       
 
   
  
