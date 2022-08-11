# Python-API-s-Challenge
Weatherpy Observable Trends from analysis results:

1. Based on the data collected for the cities used in this analysis, it is showing that there is a correlation between the latitude and max temperature for cities in northern and southern hemisphere. The data shows a negative linear regression in the cities located in northern hemisphere and positive linear regression in the cities located in southern hemisphere. Both linear regressions indicate the farther the location of the city from the equator (0 latitude), the temperature goes down thus indicating the cities that are farther from the equator has colder temperature.

2. The data points between the humidity vs latitude for cities in northern and southern hemisphere are spread out thus indicating that the city’s distance from the equator doesn’t influence the humidity. Similar trends are also showing in the analysis result for cloudiness vs latitude and wind speed vs latitude.

3. The number of cities used in this analysis are not equally distributed between the cities in northern vs southern hemisphere. The are more cities located in northern hemisphere compared to the cities located in southern hemisphere. With uneven cities distributions used in this analysis, the result is showing that this distribution doesn’t influence the obvious trend that the farther the city from the equator the colder the temperature is. It is also showing that the location and distance of the city from the equator doesn’t impact the humidity, cloudiness and wind speed.

Background
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?
Part 1: WeatherPy
In this section, you'll create a Python script to visualise the weather of over 500 cities of varying distances from the equator. You'll use a simple Python library (Links to an external site.), the OpenWeatherMap API (Links to an external site.), and your problem-solving skills to create a representative model of weather across cities.

The first requirement is to create a series of scatter plots to showcase the following relationships:

Temperature (C) vs. Latitude

Humidity (%) vs. Latitude

Cloudiness (%) vs. Latitude

Wind Speed (m/s) vs. Latitude

After each plot, add one to two sentences to explain what the code is analysing.

The second requirement is to compute the linear regression for each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere: Temperature (C) vs. Latitude

Southern Hemisphere: Temperature (C) vs. Latitude

Northern Hemisphere: Humidity (%) vs. Latitude

Southern Hemisphere: Humidity (%) vs. Latitude

Northern Hemisphere: Cloudiness (%) vs. Latitude

Southern Hemisphere: Cloudiness (%) vs. Latitude

Northern Hemisphere: Wind Speed (m/s) vs. Latitude

Southern Hemisphere: Wind Speed (m/s) vs. Latitude

After each pair of plots, explain what the linear regression is modelling. Describe any relationships that you notice and any other findings you may uncover.

Your final notebook must meet the following requirements:

Randomly select at least 500 unique (not repeated) cities based on latitude and longitude.

Perform a weather check on each of the cities by using a series of successive API calls.

Include a print log of each city as it's being processed, with the city number and city name.

Save a CSV of all retrieved data and a PNG image for each scatter plot.

Part 2: VacationPy
Now, use your weather data skills to plan future vacations. Use Jupyter gmaps and the Google Places API for this part of the assignment.
