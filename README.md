# lab2_2
lab2_2
MAIN PURPOSE:
This projects allows user to find films which were filmed nearby.
Takes into account that the movies should be in the same country/region.

WHAT YOU WILL NEED:
To install this app, you will first need to clone the repository:
$ git clone https://github.com/Vadum-cmd/lab2_2.git

Then, setup a virtualenv:

$ virtualenv -p python3 venv

$ source venv/bin/activate

Then, type the following to install the required packages:

$ pip install -r requirements.txt

(Unfortunately, file "locations.list" is to big for uploading so you'll have to unarchive it)

HOW TO USE:
To run the app type:

$ python main.py

It will then prompt you to enter your location. You need your internet connection to be stable.
You are now ready to open the map.html in your browser!

ABOUT HTML:
Folium automatiacally generates an html file containing multiple layers, with map itself, films' marks and a user location mark.

<div class="leaflet-pane leaflet-map-pane" ... >
  
This tag is a container for the map itself

<div class="leaflet-control-container">

This tag is a container for the controls.
The first one contains multiple <img> that form a map, loaded from https://b.tile.openstreetmap.org.
The second one contains buttons in <a> used for zooming and some other controls.
