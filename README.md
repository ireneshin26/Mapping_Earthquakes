# Mapping Earthquakes

## **Overview** 
In this activity, we took earthquake data from the last 7 days available on the USGS government site, added a tectonic plate overlay and major earthquake data overlay, and created additional map styles. 

## **Resources**
* Earthquake GeoJSON data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
* Tectonic Plate data: https://github.com/fraxen/tectonicplates/blob/master/GeoJSON/PB2002_boundaries.json 

## Deliverable 1: Add Tectonic Plate Data
We added a layer of tectonic plates as a second layer group using the git hub data.
![TectonicPlates](https://user-images.githubusercontent.com/110875578/200718716-b32a4cca-2ea1-4b56-8b15-8df885b8791f.png)

The tectonic plate lines are available when you first load the page.
![Steets](https://user-images.githubusercontent.com/110875578/200718887-c55d40dd-bd67-45b7-95f7-cadbf2a163c8.png)
![Satellite](https://user-images.githubusercontent.com/110875578/200719281-b7d09061-b9bc-44b4-96bf-afd71971b098.png)


## Deliverable 2: Add Major Earthquake Data
Major Earthquake layer group is added to the map. Used three colors for the circle markers for the following magnitudes; magnitude less than 5, a magnitude greater than or equal to 5, and a magnitude greater than 6. I adjusted the function to include greater than **or equal to** 5 because the module just indicated greater than 5 and there were some earthquakes being missed since they had a magnitude of 5.
![MajorEarthquakes](https://user-images.githubusercontent.com/110875578/200718918-0c4181f5-af0e-4bad-8d7b-b98ee8afa00c.png)


## Deliverable 3: Add an Additional Map
Added two new map styles: Navigation Night and Dark:
![NavigationNight](https://user-images.githubusercontent.com/110875578/200719228-52b6f688-4724-410e-b32b-cde142940a57.png)
![Dark](https://user-images.githubusercontent.com/110875578/200719254-c90dacf0-6d6c-4edd-b875-f0c65323ee81.png)
