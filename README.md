# Mapping_Earthquakes
# Project Overview
#### Basil and Sadhana like how you created your earthquake map with two different maps and the earthquake overlay. Now, Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map. The deliverables of this project includes;
1. Deliverable 1: Add Tectonic Plate Data.
2. Deliverable 2: Add Major Earthquake Data.
3. Deliverable 3: Add an Additional Map.

## Resources
### Data Source: 
- `tectonic_plate_started_code.json` 
- `major_eq_starter_logic.js`
- [](url)https://github.com/fraxen/tectonicplates/blob/master/GeoJSON/PB2002_boundaries.json
- [](url)https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

### Data Tools/Software: 
- JavaScript
- JSON
- GeoJSON
- Visual Studio Code 1.54.3.

## Deliverable 1: Add Tectonic Plate Data
> Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, you’ll add tectonic plate data using `d3.json()`, add the data using the `geoJSON()` layer, set the tectonic plate `LineString` data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data.
#### Requirements:
1. #### The tectonic plate data is added as a second layer group.
![1](https://user-images.githubusercontent.com/76136277/112700319-4165da80-8e64-11eb-937a-17eb5486c297.PNG)

2. #### The tectonic plate data is added to the overlay object.
![2](https://user-images.githubusercontent.com/76136277/112700372-62c6c680-8e64-11eb-96f5-03f7edcda2b0.PNG)

3. #### The `d3.json()` callback is working and does the following:
 - #### The tectonic plate data is passed to the `geoJSON()` layer.      
![3](https://user-images.githubusercontent.com/76136277/112700524-bc2ef580-8e64-11eb-83f8-3d0c77edacf4.PNG)
            
   - #### The `geoJSON()` layer adds color and width to the tectonic plate lines.             
![4](https://user-images.githubusercontent.com/76136277/112700633-f5676580-8e64-11eb-95e0-072222e12024.PNG)

   - #### The tectonic layer group variable is added to the map. 
![5](https://user-images.githubusercontent.com/76136277/112700737-29db2180-8e65-11eb-8fb2-78e9825081f2.PNG)

4. #### The earthquake data and tectonic plate data displayed on the map when the page loads.
![6](https://user-images.githubusercontent.com/76136277/112700920-99511100-8e65-11eb-8231-65fedc35d3e7.PNG)

## Deliverable 2: Add Major Earthquake Data 
> Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, you’ll add major earthquake data to the map using `d3.json()`, and a color and set the radius of the circle based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, `geoJSON()`.
#### Requirements:
1. #### The major earthquake data is added as a third layer group.
![7](https://user-images.githubusercontent.com/76136277/112701935-56dd0380-8e68-11eb-9222-13f323e25be0.PNG)

2. #### The major earthquake data is added to the overlay object.
![8](https://user-images.githubusercontent.com/76136277/112701976-73793b80-8e68-11eb-9a96-0a6c17a48066.PNG)

3. #### The `d3.json()` callback is working and does the following:
 - #### Sets the color and diameter of each earthquake.
![10](https://user-images.githubusercontent.com/76136277/112702061-ade2d880-8e68-11eb-8065-fd51e60c3274.PNG)

 - #### The major earthquake data is passed to the `geoJSON()` layer.
![9](https://user-images.githubusercontent.com/76136277/112702157-ef738380-8e68-11eb-873b-316ec1992171.PNG)

 - #### The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake.
![11](https://user-images.githubusercontent.com/76136277/112702206-116d0600-8e69-11eb-9d53-ec0d6b3debac.PNG)

 - #### The major earthquake layer group variable is added to the map
![12](https://user-images.githubusercontent.com/76136277/112702237-2b0e4d80-8e69-11eb-99ba-5e80cb60ea55.PNG)

4. #### All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off.
![13](https://user-images.githubusercontent.com/76136277/112702285-5729ce80-8e69-11eb-8e71-6d5d3ec724eb.PNG)

- #### Earthquake dataset toggled on
![14](https://user-images.githubusercontent.com/76136277/112702641-93a9fa00-8e6a-11eb-8e2a-bfcc61a2385f.PNG)

- #### Major Earthquake dataset togged on
![15](https://user-images.githubusercontent.com/76136277/112702654-9c9acb80-8e6a-11eb-8ecf-9777733ee556.PNG)

- #### Tectonic Plate dataset toggled on
![16](https://user-images.githubusercontent.com/76136277/112702714-e1266700-8e6a-11eb-936b-bf7c986b6648.PNG)

### Deliverable 3: Add an Additional Map
> Using your knowledge of JavaScript and Leaflet.js add a third map style to your earthquake map.
#### Requirements:
1. #### A third map tile layer is created.
![17](https://user-images.githubusercontent.com/76136277/112702856-4a0ddf00-8e6b-11eb-9fb0-fba02e483b1c.PNG)

2. #### The third map is added to the overlay object.
![18](https://user-images.githubusercontent.com/76136277/112702887-63af2680-8e6b-11eb-990d-037a463042e1.PNG)

3. #### All the earthquake data and tectonic plate data are displayed on the all maps of the webpage
![19](https://user-images.githubusercontent.com/76136277/112702939-8a6d5d00-8e6b-11eb-8709-a8f25fb6247a.PNG)

