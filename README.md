# bikesharing
Analyzing NYC Citibike data from August 2019 with Tableau.

## Overview
The purpose of this project is explore and visualize bikeshare data from Citibike in NYC. The visualizations will be shown to investors to convice them that a bike-sharing program in Des Moines, Iowa is viable and sustainable.

[Data available here](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)

## Results

[Link to Dashboard](https://public.tableau.com/app/profile/david.egri/viz/Bike_Sharing_16634709610950/CitibikeStory?publish=yes)

### Customers and Peak Hours

![Customers and Peak Hours Dashboard](/Resources/Dashboard.PNG)

This dashboard shows the total number of rides for the month of august with a breakdown by gender and customer type. In the pie charts above you can see over 3/4ths of Citibikes customers are subscribers. Citibike also has primarily male users at 65% and female following at roughly 25%. The remaining users gender is unknown or not available. The Dashboard also has an August peak hours graph showing which hours of the day had the most trips. Commute and evening times are the most popular, while late night / early morning had a significant decline in business. 

### Top Starting Locations

![Top Starting Locations](/Resources/Starting_Locations.PNG)

This visualization shows the most popular start locations for Citibike customers. The most popular location is Manhattan, which is the most popular borough for tourism. Vehicle traffic in these popular areas might have some correlation with the amount of bikes being used.

### Checkout Times for Users

![Checkout Times for Users](/Resources/Trip_Duration.PNG)

This visualization shows the check out time of the bikes for each trip taken. A majority of the trips were under 60 minutes with most trips being only 5 mintues.

### Checkout Times by Gender

![Checkout Times by Gender](/Resources/Trip_Duration_by_Gender.PNG)

This visualization is a breakdown of the check out times by duration and gender. This chart Also helps futher illustrate the difference in rides by each gender.

### Trips by Weekday per Hour

![Trips by Weekday per Hour](/Resources/Trips_by_Weekday.PNG)

The heatmap above shows how many trips were taken during different days and times of the week. Commute times and evenings have the highest usage, and the weekends with a moderate amount of usage.

### Trips by Gender

![Trips by Gender(Weekday per Hour)](/Resources/Trips_by_Gender.PNG)

This heatmap is a breakdown by gender of the usage during the week. The heatmap shows that males had a significantly higher usage rate during the week. 

### User trips by Gender by Weekday

![User trips by Gender by Weekday](/Resources/User_Trips_by_Gender.PNG)

Breaking down the weekday usage by gender and usertype really helps visualize the majority of Citibikes customers. Citibikes customer base is predominantly male subscribers.

## Summary

In conclusion the bike-sharing program in New York is a successful business, but would it be successful in Des Moines?

- In New York the customer base is predominantly male subscribers in Manhattan.
- The Most trips are taken around commuting and evening times among male and females.
- The weekend has a steady stream of moderate usage.
- a Majority of trips are under 60 minutes, with most trips being 5 minutes.

Several other factors contribute to the success of the business in New York. Bikeability, alternative transportation cost, and the cost of owning a car in the city are just a few. Some other visualizations I would suggest would be to visualize the average distance between each starting and stopping station. Getting an average distance could help plan needed station distance in Des Moines future bike-share program. Lastly, Visualizing the amount of trips taken per age would find popularity in age demographic. Comparing New Yorks highest demographic for bike-sharing with Des Moines population demographic would be insightful to our investors.