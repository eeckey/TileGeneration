# TileGeneration
Emily Eckey \
GEOG 458 Sp 22: Advanced Digital Geographies, Section AC \
Lab 4: Map Design and Tile Generation \
May 6, 2022

## Project Introduction
This project includes four tile sets of geographic phenomena. I use an index.html to visualize the four tile map sets. The map is shown in the full screen and users can use the layer switcher to turn on and off each map layer. The title and description gives insight to the user on the meaning of the layer tabs.
- [Access the Web Map](https://eeckey.github.io/TileGeneration/)

## Tile Set Layers
### Tile Set 1: Modified Basemap
![Tile 1](/img/basemap.png "Tile 1") 
- Examined geographic area: Seattle, WA [-122.2559435, 47.6002614] and surrounding area
- Available zoom layers: Min - 8; Max - 10.
- Description of tile set: Used basemap titled "Monocrome" in the dark mode provided by MapBox. Modified the basemap with font changes and size. 

### Tile Set 2: Thematic Layer of Seattle Public Art
![Tile 2](/img/tile2.png "Tile 2") 
- Examined geographic area: Seattle, WA [-122.2559435, 47.6002614] and surrounding area
- Available zoom layers: Min - 8; Max - 10
- Description of tile set: Thematic layer made by my own geospatial dataset of public art locations in the Seattle area. The public art includes - sculptures, photographs, paintings, and various installations but diferent artists. 

### Tile Set 3
![Tile 3](/img/tile3.png "Tile 3") 
- Examined geographic area: Seattle, WA [-122.2559435, 47.6002614] and surrounding area
- Available zoom layers: Min - 8; Max - 10
- Description of tile set: Layer group that is composed of a thematic layer of Seattle public art from tile set 2 and a basemap from tile set 1.

### Tile Set 4
![Smile Month](/img/smile-month.png "Smile Month") 
- Examined geographic area: Seattle, WA [-122.2559435, 47.6002614] and surrounding area
- Available zoom layers: Min - 8; Max - 10
- Description of tile set: Map layer designed over Mapbox. It embodies a map theme of May is Smile Month. The map uses the colors of yellow with blue and green environment colors and city labels to realize the theme of smiling this month!

## Data Sources
I exported a CSV format of [Seattle Public Art Data](https://data.seattle.gov/Community/Public-Art-Data/j7sn-tdzk/data) from [Seattle Open Data](https://data.seattle.gov/). I then used QGIS to create a shapefile from the CSV and save the points of each public art location in Seattle. 

## Credits
[Professor Zhao's GitHub Tutorial](https://github.com/jakobzhao/geog458/tree/master/labs/lab04)

## Acknowledgments
Thank you Professor Zhao and Jiaxin Feng for your assistance with this lab.
