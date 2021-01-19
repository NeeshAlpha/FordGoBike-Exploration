# FordGoBike-Exploration
## By: Nujood Alhajery

The seventh or last project of Udacity's Data Analysis course.
The dataset includes information about 519700 rides made in a bike-sharing system covering the greater San Francisco Bay area. The information covered includes duration, start time, end time, start station latitude and longitude, end station latitude and longitude. The dataset can be found [here](https://s3.amazonaws.com/baywheels-data/index.html).


## Summary of Findings

To achieve the findings I was looking for, I created extra columns such as distance, speed, month, time. I derived these from existing columns. Distance from the latitude and longitude columns, speed from the distance and duration columns, month and time from the start time column. 

What I may conclude is that October was the month with the most trips taken. I also found that the most frequent months for customers are September and August, and their longest duration was during June and July. whereas for the subscribers the most frequent months are October and November, however their duration spent is almost consistent throughout the whole months.

I found that the day time is when most trips are taken, and most of these trips are taken by subscribers. I also discovered that the average duration for the night trips is longer than the average duration for the day trips.

When it comes to speed, I found that subscribers take shorter and faster trips than customers. 


## Key Insights for Presentation

For the presentation I focused the most on what influences duration, speed, and distance.
I start by showing the distributions for the duration and speed. I then portray which part of the day (Day/Night) has the longest trip durations using a bar plot. After that I showed the average duration per month for each user type using a line plot. Then for the following two plots, I show the average speed and distance for each user type using point plots. Finally, I show the average duration for each user type on the two different times (Day/Night) using a bar plot. 


## Resources

- [Seaborn plots] (https://seaborn.pydata.org/index.html)

- [Pie chart ref] (https://medium.com/@kvnamipara/a-better-visualisation-of-pie-charts-by-matplotlib-935b7667d77f)

- [bins] (https://www.statisticshowto.com/choose-bin-sizes-statistics/)

- [distance calculator](# https://stackoverflow.com/questions/27928/calculate-distance-between-two-latitude-longitude-points-haversine-formula)

- [lambda function](# https://stackoverflow.com/questions/40045632/adding-a-column-in-pandas-df-using-a-function)
