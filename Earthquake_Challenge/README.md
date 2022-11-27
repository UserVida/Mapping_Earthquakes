# Overview of Project - Mapping Earthquakes

## Purpose 

The purpose of this project was to create a web app visualizing earthquake data with the use of interactive features. The earthquake data was stored in a GeoJSON file and taken from the U.S. Geographical Survey website. The data was retrieved using a combination of Javascript libraries like D3 and Leaflet. The data was then plotted on Mapbox map through an API. The finalized map has 3 map styles to choose from and 3 map layers that display the fault lines, earthquake locations and major earthquake locations (i.e. greater than a magnitude of 4.5). The markers used to represent the earthquake locations also represent the magnitude of each earthquake through the colour and size of the marker. 

## Technologies Used:
JavaScript- D3, Leaflet
Mapbox
HTML

## Procedure
The earthquake data was stored in a GeoJSON file and taken from the U.S. Geographical Survey website. The data was retrieved using a combination of Javascript libraries like D3 and Leaflet. The data was then plotted on Mapbox map through an API. The finalized map has 3 map styles to choose from and 3 map layers that:
-	display the fault lines, 
-	general earthquake locations and 
-	major earthquake locations (i.e. greater than a magnitude of 4.5). 

The markers used to represent the earthquake locations also represent the magnitude of each earthquake through the colour and size of the marker.

## Results 

![Screenshot 2022-11-12 at 22-16-18 Leaflet-Basic-Map](https://user-images.githubusercontent.com/97644424/201540729-6c6252fb-5d1c-4024-b707-545e3cf45726.png)
 
 Tectonic plate data was added using d3.json() and a geoJSON() layer. The geoJSON() layer adds colour and width to the tectonic plate lines. Finally the tectonic plate layer is added an an overlay object.

 ![Screenshot 2022-11-12 at 22-16-59 Leaflet-Basic-Map](https://user-images.githubusercontent.com/97644424/201564400-83a6efae-46a7-495a-9745-aa408442cbbc.png)

 The major earthquake data, that is earthquakes over the magnitude of 4.5, was added to the map using d3.json(). The colour and radius of the circle markers were based on the magnitude of the earthquake. A pop-up marker that appears when one of the circle markers is hovered over, shows the magnitude and location of the earthquake. This pop-up marker was also added using the geoJSON() layer. 

![Screenshot 2022-11-12 at 22-17-19 Leaflet-Basic-Map](https://user-images.githubusercontent.com/97644424/201565035-fcbb503b-369f-4b6e-9c7a-8b1194e01ebb.png)

A light mode map style was added as a third tile to the map.

### Authors
•	Zainab Cheentavida  
