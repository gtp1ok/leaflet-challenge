# leaflet-challenge
Module 15 Challenge
Leaflet Homework - Visualizing Data with Leaflet
Header

Viewing the Map

In order to view the map, you will need to generate your own API Key from : https://www.mapbox.com/
This will need to be placed in either of the project folder(s) '/static/js/config.js', and the HTML and JS files changed to ensure the correct file paths are being used for visulisation.
In order to visualise the map, you will need to spin up a local http server for this to run on.

Using your command prompt (Git Bash), navigate to the directory where you have saved the index.html file, then run the command 'python -m http.server'
This will open up the index.html in your web browser and have it running on a server, local to your machine.

Alternatively, you can also use a plugin within VSCode, such as 'Live Server'


About the Map

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. The dataset that has been utilised in this project is 'All Earthquakes from the Past 7 Days'. When visiting the USGS GeoJSON Feed you can see a JSON representation of datasets available.

Base & Overlay Layers


The ability to turn on and off layers to see earthquake data is available. There is also a number of base layer maps that can be utilised depending on your preference. As a default, the street map, earthquake and techtonic plates will all be loaded into the map when first opened, and can be turned on and off as you wish.


Markers

1. Each of the earthquake markers (cirlces) can be clicked to visualise more infomration about the earthquake such as a description of the location, magnitude and      depth.
2. When visualising the map, each of the earthquake markers (cirlces) are identified by 2 properties. The size of the marker, relates to the size of magnitude and the colour relates to the depth of the earthquake as seen on the legend positioned in the bottom right hand corner of the map.


Created With
This project was created using the following:

Leaflet
Mapbox
D3
JavaScript
Bootstrap
HTML
CSS
