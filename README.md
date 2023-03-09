# Module 15 Challenge
## Mapping on the Web

# Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

This project will use leaflet, javascript, and D3 to visualize earthquake data from USGS.

# Part 1: Create the Earthquake Visualization
## Get the Data
* The USGS provides earthquake data in a number of different formats, updated every 5 minutes
* The "All Earthquakes from the Past 7 Days" data set was selected from the USGS GeoJSON Feed page
* The data was given in JSON format which was used to pull in the data for the visualization
## Import and Visualize the data
* Data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. 
    - Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
* Include popups to provide additional information about the earthquake
* Create a legend that will provide context for map data
