# BootCamp_leaflet-challenge

## Part 1: Create the Earthquake Visualisation

Your first task is to visualise an earthquake dataset. Complete the following steps:

1. Get your dataset. To do so, follow these steps:

    - The USGS provides earthquake data in a number of different formats, updated every 5 minutes. [Visit the USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and choose a dataset to visualise. The following image is an example screenshot of what appears when you visit this link:
    - When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualisation. The following image is a sampling of earthquake data in JSON format:
  

2. Import and visualise the data by doing the following:

    - Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
    
        - Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by colour. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in colour.
        
        - Hint: The depth of the earth can be found as the third coordinate for each earthquake.
    
    - Include popups that provide additional information about the earthquake when its associated marker is clicked.
    
    - Create a legend that will provide context for your map data.
    
    - Your visualisation should look something like the preceding map.
  
![Map](Leaflet-Part-1/Images/Map.png)
