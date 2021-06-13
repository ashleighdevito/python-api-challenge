# python-api-challenge

This project contains a Jupyter Notebook analysis of weather condition across the globe, looking for an optimal vacation destination.

##### WeatherPy

Conclusions are highlighted below each plotted figure.  The weather data was gathered from current condidtions through the OpenWeatherMap API for cities randomly selected using the citypy Python library.  Conditions recorded for each city were:

    Maximum Temperature
    Humidity
    Cloudiness
    Wind Speed
    
All points obtained to describe the day of 6/13/2021. The data was cleaned and conditions were compared to the distance of that city to the equator. Plots included:

    Temperature (F) vs. Latitude
    Humidity (%) vs. Latitude
    Cloudiness (%) vs. Latitude
    Wind Speed (mph) vs. Latitude

Regressions are calculated on the same data divided by hemisphere. These were added to additional plots.

    Northern Hemisphere - Temperature (F) vs. Latitude
    Southern Hemisphere - Temperature (F) vs. Latitude
    Northern Hemisphere - Humidity (%) vs. Latitude
    Southern Hemisphere - Humidity (%) vs. Latitude
    Northern Hemisphere - Cloudiness (%) vs. Latitude
    Southern Hemisphere - Cloudiness (%) vs. Latitude
    Northern Hemisphere - Wind Speed (mph) vs. Latitude
    Southern Hemisphere - Wind Speed (mph) vs. Latitude
    
All scatterplots are exported and saved into the output folder, within images.

##### VacationPy

The data cleaned for the weather analysis is then used to create a global heatmap of humidity.  Potential vacation locations are identified by optimal weather conditions.  The criteria used is:

   * A max temperature lower than 80 degrees but higher than 70 (F)
   * Wind speed less than 10 mph
   * Zero cloudiness
    
Hotels are found for each qualifying city and markers with their information are displayed overtop of the global humidity heatmap.

Screenshots of the resulting maps can be found within the output folder, within images.
