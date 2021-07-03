# PyBer_Analysis  

## Overview of Analysis  
PyBer is a ride-sharing app company valued at $2.3 billion and they just asked for the analysis of its rideshare data from January to early June of 2019, this analysis aims to use the data provided in a CSV file format from where we will group by different location types: Urban, Suburban, and Rural to be able to represent the total weekly fares for each location.  

## Results  

### DataFrame Analysis  
The analysis indicates that the total rides in the Urban area is higher than the rides from the Rural and Suburban areas the lowest being in rural areas, the total number of drivers is also the highest in urban vs suburban or rural areas as well as the total fares; The average fares on the other hand are different from the previous results in that they rank from the highest in the rural "$34.62 per ride" vs suburban or urban areas.

![pyber_summary_df](https://user-images.githubusercontent.com/16723095/124365981-ad00d600-dc11-11eb-8d30-1888feffd6b3.PNG)

### Charting the Fares by City Type Over Time
The line chart of this dataframe indicates that there is an upward trend in the number of rides in early January 2019 in urban and suburban areas but not in the rural areas which might be due to a lower interest to take such services early in that month in Rural areas, we can observe an increase in the number of rides by mid February for all the areas declining towards the beginning of March, by April the Rural area has a bigger peak in Fares followed by the Urban area not been the same for the Suburban area that decline to start rising again by the middle of April.  

![PyBer_fare_summary](https://user-images.githubusercontent.com/16723095/124365922-103e3880-dc11-11eb-924c-bcd6fe297f21.png)

## Summary
- There seems to be a disproportionately large number of rides in urban areas versus suburban or rural areas and on the other hand the fare per ride in rural areas is the highest, a normalization of the fares in rural areas may be helpful in more rides in such areas.  

- While the number of drivers in the Urban area is greater than the Suburban area 2405 vs 490 nearly 5 times, the total revenues from such areas is only twice as much as suburban areas, therefore allocation of a number of drivers to suburban and to a lesser degree to rural areas deems to be advisable.  
