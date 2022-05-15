
# GeoCoord - Simple utility to play with geocoordinates

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martialpohin/geocoord.git/master?labpath=notebook%2Fgeocoord.ipynb)


GeoCoord is a tool build for pedagogic aspect only. 
It must not be used for any other objectives than for learning objectives. 

It can be used using mybinder.org.

The first objective is to illustrate resolution of geocoordinates in front of usage of the point, in this case movement at a certain speed, and during a certain duration. 

## Manual

### position tab

* It allows to define a geocoord using different format, and it is displayed on the map, with rectangle which size is define using resolution of the position +/- 1 on lower digit.
* Conversion to other general use format is also provided.

### Speed tab

* Based on the previous position, and range of duration, and range of speed, it draws circle around the point.

## With the help of 

* [ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/index.html)
* [ipywidgets](https://ipywidgets.readthedocs.io/en/latest/)
* [pyproj](https://pyproj4.github.io/pyproj/stable/)
* [Aerocalc3](https://geoffreynyaga.github.io/aerocalc/)