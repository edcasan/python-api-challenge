
Creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator, utilizing a simple Python library, the OpenWeatherMap API, and a little common sense creating a representative model of weather across world cities and scatter plots, linear regression on each relationship.

Each pair of plots explain what the linear regression is modeling such as any relationships you notice and any other analysis I may have.
The final notebook shows:

Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name,
Save a CSV of all retrieved data and a PNG image for each scatter plot.

Using jupyter-gmaps and the Google Places API creation a heat map that displays the humidity for every city,
Narrow down the DataFrame to find your ideal weather condition,
A max temperature lower than 80 degrees but higher than 70.
Wind speed less than 10 mph.
Zero cloudiness.


Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.



![image](https://user-images.githubusercontent.com/63757160/109586877-b3e4d400-7acb-11eb-885e-9aa728a3be35.png)

![image](https://user-images.githubusercontent.com/63757160/109586921-ce1eb200-7acb-11eb-80ee-444a65f5fe84.png)

![image](https://user-images.githubusercontent.com/63757160/109586966-e1318200-7acb-11eb-9433-550c967811a5.png)

![image](https://user-images.githubusercontent.com/63757160/109587019-f5757f00-7acb-11eb-89ac-8cb67d519426.png)

