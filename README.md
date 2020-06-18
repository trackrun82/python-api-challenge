# python-api-challenge

This challenge was to the OpenWeather API to look at several relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

These relationships were also looked into separately for the Northern and Southern hemispheres.

Using the randomly selected cities (>5000), a heat map was made for Humidity using gmaps.  This city dataset was narrowed down to ideal conditions for vacationing (<10) and hotels were found within 5000 meters of these ideal cities using Google Places API.  Markers were overlaid on the previous gmap heatmap and info was tied to each marker.
