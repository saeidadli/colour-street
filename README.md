# Colour Streets

**Colour Street** draws a colour-coded street network of a city. It was originally done by [Giuseppe Sollazzo](https://github.com/puntofisso/OSMnxNotebooks/blob/master/Street%20colouring.ipynb) but I made few changes and upgrades. The [example notebook](https://github.com/saeidadli/colour-street/blob/master/ipynb/example.ipynb) works for Auckland and should work for other cities too. 

## How to use Colour Streets

First, make sure you have the following libraries on your Python 3.6+:
  * sys
  * pathlib
  * osmnx
  * pandas 
  * geopandas 

Second, draw a boundary around the city you want to colour its streets. You can use simple web application such as [geojson.io](http://geojson.io/).

Third, copy the city boundary (a GeoJSON file) to the data folder.

Fourth, run the code and enjoy your graphic.