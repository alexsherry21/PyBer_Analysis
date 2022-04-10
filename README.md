# PyBer_Analysis
Python, Jupyter, Matplotlib work for Module 5

## Overview
The purpose of this analysis was to learn to visualize PyBer's ride data in different ways to provide recommendations for the company.  We will use Python with the Pandas and Matplotlib libraries to analyze and display the data.

## Results

### Fare Summary Data
To begin, we imported both the Pandas and Matplotlib libraries to load the data into our file and build an initial DataFrame out of our two excel files from PyBer.  Primarily, we used the groupby() function to split ride, driver, and fare data between urban, suburban, and rural cities.  After restricting our data to dates January 1, 2019 to April 28, 2019, 

![Fares DataFrame](https://user-images.githubusercontent.com/100380226/162595726-83768849-fdec-4b96-bfa6-0b7f94d14fea.png)

Between the types of cities, there is a clear trend of a greater number of rides at a lower price occuring in more densely populated areas.  This appears to make sense as cities have the highest population and hypothetically should have the shortest trips on average, while trips could be further and longer in the suburbs, and even more so in rural areas.  Additionally, the urban group is the only one with more listed drivers than rides in our time span.

### Changes in Fares Over Time
Matplotlib also allowed us to plot the total weekly fare revenue for each city type from January through April.

![PyBer_fare_summary](https://user-images.githubusercontent.com/100380226/162595775-5c2bd828-0256-4744-b907-dcb18fbfb7e0.png)

While there is some fluctuation over the weeks, it is hard to determine what could cause it as all three lines are pretty consistent, with the only possible trend being a very slight increase in total fares over time, mostly expressed in the urban and rural lines.  The only universal spike in total fares is late in February which is difficult to explain as it is clearly after Valentine's Day (near which fares were actually lower) and not near any other major holidays.

## Summary
The most notable disparity among the city types is that in urban cities drivers outnumbered rides in our time period, which is not good for the drivers.  While the average fare per ride is significantly lower than in the other two categories, $24.53 averages within a city could be steeper than people want to pay in the moment.  If you need a ride out in the country, you don't have a lot of options.  Walking is sometimes chosen over calling a ride when it is an option, and in cities it often is.  My first recommendation is to offer discounts for repeat riders.  This would lead to people calling more PyBer rides, generating more revenue and assisting our idle drivers.  It would also help retain users, which is valuable when people have many apps at their disposal.  My second recommendation is increasing driver compensation and benefits.  PyBer is competing not only for customers but also for employees.  An average fare per driver of $16.57 will no doubt lead to frustration and they could potentially seek out other apps or industries entirely.  Lastly I would try to invest in a way to optimize the winter.  In our sample, PyBer rides were at their lowest in January.  This is just one idea, but PyBer could offer salt delivery or application services to consumers in order to supplement the lower number of rides that drivers are getting.  Alternatively, PyBer could buy plow blades to fit onto larger vehicles and possibly contract snow services.  Offering these services would also allow PyBer to more efficiently deploy its driver fleet in the winter in order to better take advantage of a lower potential number of rides.
