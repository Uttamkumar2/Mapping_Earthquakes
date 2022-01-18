# Mapping_Earthquakes

## Project Overview 

The Objective of this project is to Visualize & creating interactive work map using Earthquake GeoJSON Data with the help of Javascript Visualization Libraries like D3 , MapBox API, Leaflep. GeoJSON data has many applications such has Ride sharing, navigation, Tracking Location extra. The GeoJson data is industry standard to representing simple Geographical features and non-special attributes. 
    We have used Geographical Feature like 
    
         •	Points, which contains address and location, like latitude and longitude coordinates.
         •  Linestrings which contains coordinates for the boundaries  streets, highways travel routes and tectonic plates.
         •  Polygon which contain coordinates for the boundaries of zip codes, countries, province and track of land.

The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event's magnitude.

## Resource 
1. **DataSource** 

    •   https://github.com/fraxen/tectonicplates/blob/master/GeoJSON/PB2002_boundaries.json
    
    •   https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson
    
2. To create tyleLayer created an account in MapBox, which gave me API Config key token to access Mapbox API.
   As shown below, index.html calls for the Mapbox API key in config.js file.

    ![call_api_congf](https://user-images.githubusercontent.com/91766890/149880977-5c7c7919-c0fb-4eb0-a5f7-b30803c2aa71.PNG)

    ![api_key](https://user-images.githubusercontent.com/91766890/149881014-5dd5df6e-c7e3-45ab-9cda-170846c126c1.PNG)

3. **Software**: Visual Studio Code, JavaScript, HTML/CSS, Leaflet, D3.js
4. To Open index.html, either in Visual Studio Code right click and "open with live server" or go to terminal and type
    
    **Python -m http.server.**

## Results

## Interactive Maps Views
### Streets view

![streets](https://user-images.githubusercontent.com/91766890/149881115-d1ad7ec6-3bcf-4ba5-8b46-79fc838cb4de.PNG)

### Satellite view
![setellite](https://user-images.githubusercontent.com/91766890/149881132-1ffd5bee-7ca3-4d4c-9a59-30896b656eb7.PNG)

### Dark View
![dark](https://user-images.githubusercontent.com/91766890/149881152-41e23f48-8b7a-4a27-aacb-78a9359989c2.PNG)

