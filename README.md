# PyBer Analysis

## Project Overview
  The purpose of this project is to evaluate PyBer ride sharing data across three distinct city types – Urban, Suburban, and Rural. This analysis will include ride count, driver count, and fare data from January 2019 through April 2019 to determine what opportunities, or next steps, exist to enhance service and company revenue. 

## Resources 
  - Software:  Python with pandas and matplotlib libraries
  - Platform:  Jupyter Notebook, via Anaconda
  - Data Sources:  city_data.csv, ride_data.csv

## Summary of Results
   Overall, this data doesn't uncover anything too surprising. It falls in line with common sense ideas when someone thinks about how people use PyBer across these three unique city types. By splitting the data based on geographical populations, it allows a better understanding of how PyBer is used, how drivers are impacted, and where revenue is generated. 

I will dissect each type of city and then provide an overview of how they relate to one another. Below you will find a table that illuminates key metrics across the three groups.


<sub>*PyBer Summary Table*<sub/>
  
![PyBer_summary_table](https://github.com/Kelfang/PyBer_Analysis/blob/main/analysis/PyBer_summary_table.png)


### Urban Ride Data
  As one might suspect, the urban demographic held the highest number of total rides and the highest number of total drivers among the three groups. This makes sense due to population density - the larger the population the more rides and the more drivers. On the other hand, the “Average Fare per Ride” was the lowest among the three categories. This should be expected since urban destinations are geographically concentrated and the distance from one location to another are often shorter distances that take less time. That translates to more rides with a lower average fare.
  
  Another item of note is the fact that there are 780 more drivers than there are rides in the urban sector, which lowers the “Average Fare per Driver” in a drastic way. This kind of internal competition could keep pricing lower to entice riders to book the trip and give as many drivers as possible the chance to earn income.  As you can see, the “Average Fare per Driver” drops almost $8.00 from the “Average Fare per Ride”, which means there are far more drivers than the riders can support. 

### Suburban Ride Data
  Moving onto the suburban scene, this data falls right down the middle of the three groups. A suburban setting is often more spread out which explains why the “Average Fare per Ride” is higher than its urban counterpart. The rides are longer and, therefore, more expensive. Many suburban dwellers also have their own vehicles which would reduce the number of rides as well. 
  
  Within the suburban group there are 490 drivers that gave 625 rides over the 4-month period, that roughly equates to 1.27 rides per driver. This means all the drivers likely participated in earning income during that time. This is further evident when looking at the $8.53 increase found in the “Average Fare per Driver” over the “Average Fare per Ride”.  

### Rural Ride Data
  The rural sector had the lowest number of rides, total drivers, and total fare which one would expect from this data. Rural areas are spread out with homes scattered, often miles apart. People typically reside in these areas with intention, prioritizing open spaces and undeveloped land over the convenience of proximity to stores, restaurants, airports, or other common destinations. A personal vehicle is essential among this demographic so PyBer use would be more infrequent. 
  
  The drivers in the rural areas often have longer trips, but they are likely earning the most of all categories with $55.49 as the “Average Fare per Driver”. Digging into this number further, you’ll see that it’s an increase of $20.87 over the “Average Fare per Ride”. Additionally, the 78 rural drivers booked 125 rides which means each driver averaged 1.6 rides during that 4-month timeframe. 

### Overall Ride Data
  In evaluating this data at a higher level, you can see that the urban group generated the highest “Total Fares”, which is directly correlated to the number of rides. There are also more than enough drivers to meet those needs so it’s highly probable that no ride request goes unfulfilled. However, the urban community is saturated with drivers when compared to the suburban and rural communities. This fact is reflected in three key areas: “Total Rides”, Total Drivers”, and “Average Fare per Driver”. Both the suburban and rural drivers earn a more favorable income than the urban drivers, on a per ride basis. However, the “Total Rides” volume is far less in the suburban and rural areas which may impact the appeal of drivers to participate in those communities. In general, the drivers may have a default assumption that there is more opportunity in the urban setting than the suburban or rural. The data provided here, shows otherwise. 
  
  Looking at the graph below, you can see that the suburban and rural usage are similar in their peaks and valleys. The urban activity seeming to exhibit a more predictable pattern. While all three categories have their ups and downs, the suburban group seems to have the largest swings in usage. This could make forecasting needs for future drivers difficult. The rural group, even with the lowest total fare, still seems to have some reliability with it’s tempered line.   


<sub>*PyBer Fare Summary*<sub/>
![PyBer_fare_summary](https://github.com/Kelfang/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)


## Final Thoughts
  While this data doesn’t provide us with all the details, I do believe it gives us enough information to determine some next steps.  

*	I would further evaluate rural and suburban behaviors. Are rides being requested that are going unfulfilled? Are there rides that are not booked due to cost or timing of driver arrival? Since these two areas have more rides than drivers, while the numbers seem manageable, is there money being left on the table? 
* Recruit urban drivers to service the suburbs and/or rural areas near them. This further illustrates the benefits of my first point, to include a deeper dig into when the suburban and rural areas experience “peak usage” and incentivize urban drivers to book those trips. Often, the rural and/or suburban passengers are heading into more densely populated areas where additional rides could be booked after those rides conclude. 
* Analyze a full year of data. While this 4-month window is a good place to start, I wouldn’t make any sweeping changes until more data is evaluated. As we all know, there are seasonal impacts that change human behaviors, like weather or cash flow. For example, restaurants in January have notoriously low turnout due to tighter budgets following the holidays, weather in certain parts of the country, and those New Year resolutions to work out more and eat less. These metrics could change significantly over the course of a year and some changes could be warranted for only a short period of time. 

