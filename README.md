# Surfs Up Analysis

## Overview

A surf and ice cream shop in Oahu is trying to determine if they should stay open year-round by analyzing the temperature differences between a winter and summer month. In order to do this, they have requested an analysis of the temperature differences specifically between June and December. Using Python, Pandas functions, and SQLAlchemy, we were able to retrieve temperatures, put them into DataFrames, and generate summary statistics for each month. 

## Results

- The biggest difference between June and December months in Oahu is the low temperatures. There is an 8 degree difference between each months lowest temperature recorded.

- The smallest difference was the maximum temperature: June's maximum temperature was only 2 degrees higher than December

- All other statistics were only about 3-4 degrees higher in June than in December 


![June_Summary_Stats](https://user-images.githubusercontent.com/114192448/209022572-fe3f4770-673d-42ed-bebc-8dc8a42a0263.png)
![Dec_Summary_Stats](https://user-images.githubusercontent.com/114192448/209022585-2771e692-0119-44e8-814a-582d991316c9.png)



## Summary

Upon review of the results above, the temperatures in Oahu between June and December are very similar, with December only seeing a very slight decrease in temperature. This might lead one to then believe that the summer and winter months on Oahu are comparable, therefore the surf and ice cream shop should see no issue with remaining open all year. However, this data only gives us a very small, very specific bit of information on the weather during summer and winter. In order to get a broader idea of the seasons and their weather, the additional queries could be run:

### 1. Temperature for the entire season
In order to get a better idea of what Oahu feels like during the winter and summer months, a query could be run to pull temperature information for multiple months to represent the season. (For example, June through August could be pulled for summer, while December through February could be winter.) We could create a DataFrame out of those temperatures and pull summary statistics, as we did with this analysis. In this example, we would be pulling from a much larger dataset of temperatures to analyze.

### 2. Pull precipitation information
Two days can have the same temperature, but still have drastically different weather. That's why it would be inportant to also pull information on precipitation during the winter and summer months in order to get a more comprehensive view of the difference in weather. A customer is much more likely to get an ice cream on a sunny 70 degree day, rather than on a stormy 70 degree day.
