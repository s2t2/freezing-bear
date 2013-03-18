Make sure to [close](http://stackoverflow.com/q/15456176/670433) GeoJSON features like Polygons and MultiPolygons by repeating the starting coordinate again at the end. 

While leaflet seems to handle features without closure, d3 does not provide the same leniency.

Resources:
 + [county geojson data](https://github.com/johan/world.geo.json/tree/master/countries/USA/CT)
 + [d3 with leaflet](http://bost.ocks.org/mike/leaflet/)
 + [d3 transitions](http://bost.ocks.org/mike/transition/)
 + [d3 geo paths and projections](https://github.com/mbostock/d3/wiki/Geo-Paths)
 + [d3 mouseover events](http://bl.ocks.org/mbostock/1087001)

