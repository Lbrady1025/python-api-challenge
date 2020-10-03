# python-api-challenge
CWRU Homework Week 6

This homework assignment involves using Python APIs to request data, and then visualize it in a way that makes sense. The project was done using a Jupyter Notebook.

### WeatherPy
This project pulls weather data from 500 randomly selected cities using the Citipy library and the OpenWeather API. Analysis is then performed and visualized using Pandas and MatPlotLib in order to show whether there is a relationship between latitude and the following data points: temperature (F), humidity (%), cloudiness (%), and wind speed (mph). All of these data sets are then broken out between the northern and southern hemisphere and compared to see if there are any statistically significant differences between the two hemispheres.

### VacationPy
This project uses the cities identified in the previous project and the Google Maps API to create a heatmap based on percent humidity. The results are then narrowed down to find "perfect vacation conditions", which includes a temperature between 70F and 80F, zero cloudiness, wind speeds below 10 mph, and humidity below or equal to 75%. The Google API was then used to identify a hotel close to these city locations and mapped onto the heatmap using markers.

All figures and screenshots of the Google Maps are included in the "Results" folder of this repository. Analysis was performed on 09/05/2020 and 09/06/2020.
