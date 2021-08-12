### GIS (Geographic Information System)

* A GIS is a SYSTEM to capture, store, check and display data related to positions on Earth's surface.
* Uses any information that includes location (latitude, longitude, address or ZIP code).
* Include data such as population, income or education level.
* Can keep the data about the landscape, such as the location of streams, different kinds of vegetation, and different kinds of soil.
 
<img src="./image/GIS.jpg" >

#### ArcGis (https://www.arcgis.com/index.html)
* A GIS system developed by Esri, writen in C++.
* It has a base layer with a geographical map pulled out of a range of sources (satellite, road map, etc).
* Then, the first three layers are called feature or vector layers, each containing individual functions distinguished through the platform.
    * points (landmarks, buildings)
    * lines (roads, 1D schemata)
    * polygons (political information, geographical census, 2D data)
    * raster images (base vector layer like an aerial picture)

### File extension Keyhole Markup Language (KML)

* Use XML to express geographic annotation and visualization
* Store locations, image overlays, video links and modeling information like lines, shapes, 3D images and points.
* Google Earth was the first program to be able to view KML files.

### Shapefile

* Shapefile is a file format to store vector data developed by Esri.
* First used in the ArcMap System.
* The default pattern to keep these files is in a *ZIP*.
* So inside this *ZIP*, at the root directory it has at least one *.shp* file, one *.shx* file, one *.dbf* file and one *.prj* file.
* ArcGis does not accept Shapefile that have
    * multipatch or multipoint geometries
    * geometries that cross the dateline
    * self-intersections in polygons

### Shapefile vs KML

* [Mark Cupitt](https://gis.stackexchange.com/users/17846/mark-cupitt) says:

```
KML and Shapefiles could contain the exact same data, however KML is much more suited to displaying time based track information, whereas shapefiles are more suited to displaying Geometries, like boundaries, areas, roads, etc.
```

### Examples

* [Good example of GIS](https://learngis.maps.arcgis.com/apps/View/index.html?appid=c38aaa416d984250870bffa33b5f91ee)

#### References

* https://www.nationalgeographic.org/encyclopedia/geographic-information-system-gis/
* https://www.geospatialworld.net/blogs/what-is-arcgis/
* https://www.lifewire.com/kml-file-4140272
* https://enterprise.arcgis.com/pt-br/portal/latest/use/shapefiles.htm#:~:text=Um%20shapefile%20%C3%A9%20um%20formato,cont%C3%A9m%20uma%20classe%20de%20fei%C3%A7%C3%A3o.

## Homepage

[Back](../README.md)