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
       
 
   
  
