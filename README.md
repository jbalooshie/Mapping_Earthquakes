# Mapping_Earthquakes

# Project Overview

This repository was created as part of a 6 month Data Analystics Bootcamp administed by George Washington University. This is the repository for the Module 14 Challenge. The purpose of this project was to create an interactive map showing earthquake activity across the world. The Leaflet API was utilized to create the map, and markers and overlays were added using Javascript to visualize the earthquakes. The markers are color coded and scaled based on the magnitude of the earthquake and can be clicked to pull up more specific information about the earthquake magnitude and location. Overlays are available to show major earthquakes and tectonic plates. Earthquake data is provided by the USGS. 

Below is an image of the map with all overlays enabled. 


![Image of Map](https://github.com/jbalooshie/Mapping_Earthquakes/blob/main/images/map.PNG)

## Viewing the Project
To view the project locally, you will need Python and a Leaflet API key. Clone the repo. In the folder Earthquake_Challenge/static/js create a javascript file named 'config'. Save your Leaflet API key there as a variable named 'API_KEY'. Then use Python to run a local web server, and open the index.html file. The interactive map will pull up and you can view the project. 