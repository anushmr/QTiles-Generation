# **<span style="font-family:'Playfair Display',serif;font-size: 1.5em;">QTiles Generation</span>**

## **<span style="font-family:'Playfair Display',serif;font-size: 1.3em;">Trauma Hospitals in King County, WA</span>**
### **<span style="font-family:'Playfair Display',serif;font-size: 0.8em;">Author: Anush Mughnetsyan</span>**



### **<span style="font-family:'Playfair Display',serif;font-size: 1em;">Maps</span>**
[Web Map - Seattle Tile Sets](https://anushmr.github.io/QTiles-Generation/index.html) 

![Light Mapbox](img/light_Mapbox.png)
Light Basemap by Mapbox

![Hospitals Layer](img/hospital.png)
Geospacial dataset with modified monochrom basemap by Mapbox 

![Basemap Layer](img/basemap_Cartogram.png)
Thematic layer created with Cartogram by Mapbox

![Basemap and Hospitals Layer](img/basemap_hospital.png)
Combined thematic layer and geospacial dataset

![Sleepless in Seattle Theme Layer](img/thematic.png)
Custom design of Monochrom Midnight basemap by Mapbox

### **<span style="font-family:'Playfair Display',serif;font-size: 1em;">Description of Maps</span>**
- I used the greyscale basemap, which is one of the basic  layers by Mapbox, to show the contrast between the rest of all the custom designed maps. 
- All the layers were generated using QGIS QMetaTiles plugins.
- Hospitals layer has simplified Monochrom Sky basemap that hosts all the trauma hospitals in King County, WA.
- Thematic layer was inspired my [Stamen Watercolor basemap](http://maps.stamen.com/#watercolor)
- The next layer is a combination of the thematic and geospacial dataset layers.
- The last layer is custom modified using the Monochrom Midnight basemap by Mapbox. It highlights the artery of roads and bridges across Seattle and King County. I named this layer "Sleepless in Seattle."
- Each layer has zoom layer 0-14


### **<span style="font-family:'Playfair Display',serif;font-size: 1em;">Data Sources</span>**

- Mapbox Studio was used for custom design of all the presented layers.
- The data used to make the hospital layer was gathered from
[King County GIS Open Data](https://gis-kingcounty.opendata.arcgis.com/datasets/kingcounty::acute-service-hospitals-in-king-county-hospitals-point/explore?location=47.542492%2C-121.988865%2C10.00)
This dataset presents trauma hospitals across King County, WA for emergency planning and general analysis.
- Watercolor basemap by Stamen was used to create a custom layer in Cartogram by Mapbox
![Watercolor basemap by Stamen](img/Cartogram_colors.png)