# PyBer Analysis
## Overview of the PyBer Analysis
### Purpose
PyBer, a ride sharing app company, tasked us with analyzing data to help improve access to ride-sharing services and determine affordability for underserved neighborhoods. We created a DataFrame to analyze the total weekly fares by city type. From this DataFrame, we then created a line graph to aid our findings for PyBer’s CEO.
## Results
<img width="600" alt="PyBer_fare_summary_dataframe" src="https://user-images.githubusercontent.com/103657822/170894087-e4142b55-ff42-4d15-9022-2aeb8ebae65c.png">
Through creating our summary DataFrame for PyBer, we found the number of total rides, drivers, fares, the average fare per ride, and the average fare per driver. As you can see, Urban city types had the most total rides, drivers, and fares with 1,625 number of rides, 2,405 number of drivers, and $39,854.38 total fares. The average fare per ride was $24.53 and the average fare per driver was $16.57 for Urban cities. Suburban cities had 625 total rides, 490 total drivers, and $19,356.33 in total fares. Their average fare per ride was $30.97 and average fare per driver was $39.50. Whereas rural cities had the least amount of rides, drivers, and fares. The total rides for rural cities was 125 with 78 total drivers and $4,327.93 in total fares. The average fare per ride was $34.62 and the average fare per driver was $55.49. After reviewing this data, it makes sense when you think about the population differences in urban, suburban, and rural areas.
<img width="249" alt="week_fares_dataframe" src="https://user-images.githubusercontent.com/103657822/170894905-97b95aed-58c3-41f8-93f5-41075c4e19ff.png">
<img width="793" alt="PyBer_fare_summary_linechart" src="https://user-images.githubusercontent.com/103657822/170894909-0e6802d3-7ca6-46b4-9a71-a0c16734a6d1.png">
To create our line graph, we made a weekly fare summary for PyBer (a snippet of the DataFrame is displayed above). As you can see, urban and suburban cities are pretty constant in the weekly fares proabably due to population size and a constant flow of tourists and events within the city. Come mid February, however, there is more growth within the weekly fares for urban and suburban cities. As for rural cities, there are continual ebb and flows. The ebbs and flows of all of these lines are probably caused by weekends, events, or tourists. 

## Summary
The biggest disparity is the number of drivers to number of rides between the different city types. The most significant disparity is that you have more drivers than rides for the urban cities. There is a surplus of drivers. I would reccommend to decrease the total number of drivers. By decreasing the number of drivers, the current drivers would be able to make more money. Another recommendation that I have is to implement a rewards program that once a rider hits a total number of rides or points then they get a free ride. This would encourage customer retainability and can be used to market to new customers. Also, the rewards program would increase the number of rides which would make the current ride to driver ratio more appropriate. The final recommendation that I have is to research data on the cost per mile and the average mileage per ride. This information would allow us to determine how mileage and driver supply and demand affect cost and affordabililty in the different city types. Additionally, you are then able to make a conclusion on the most optimal ratio of rides to drivers which as a result generates affordability.
