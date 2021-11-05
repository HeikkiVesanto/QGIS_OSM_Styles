# QGIS_OSM_Styles
QGIS Styles for Geofabrik OpenStreetMap Extracts

The Stamen toner background mapping tiles are a classic of the GIS industry. Really well made and great design: http://maps.stamen.com/toner/

However they don't work so well when you are exporting the data at a high DPI from QGIS. Since they were made for web mapping.

I wanted to put together some styles that could be used with the Geofabrik (https://download.geofabrik.de/) OpenStreetMap Shapefile extracts, since those are the easiest for new users to work with.

These styles you just need to copy into the same folder as your Shapefiles before loading them into QGIS, put them in the same order as in the picture (order.png), and then once loaded they should symbolise correctly.

Note: there is one caveate to this. The Geofabrik extracts do not contain a land/ocean layer. So you can create one. For Ireland using a filter on gis_osm_places_a_free_1: "fclass" = 'Island' is a good approximation. And there are then 2 styles for it, you just add the data twice, filer it, and add the styles to the two layers. Or you can use the land polygons from: https://osmdata.openstreetmap.de/data/land-polygons.html

Any questions leave a note here.

These are also version 1. So there may be some updates.
