#### Data Format

We need **GeoJSON data** about the borders.  
Precisely, [Polygon](https://tools.ietf.org/html/rfc7946#section-3.1.6) & [MultiPolygon](https://tools.ietf.org/html/rfc7946#appendix-A.4) data.

#### Resources for country data

- [https://www.kaggle.com/chapagain/country-state-geo-location](https://www.kaggle.com/chapagain/country-state-geo-location)  

  Similar to #2

- [https://github.com/johan/world.geo.json/blob/master/countries.geo.json](https://github.com/johan/world.geo.json/blob/master/countries.geo.json)  

  This is the best one by far for countries data by size.

- [https://www.naturalearthdata.com/downloads/10m-cultural-vectors/](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/)  

  Looks like the most trustworthy but file size is too large.

- [https://github.com/stefanocudini/geojson-resources/blob/master/world.json](https://github.com/stefanocudini/geojson-resources/blob/master/world.json)  

  Doesn't have the country codes. Instead it has Feature ID so not of much use.

- [https://data.world/dgreiner/world-spatial-data](https://data.world/dgreiner/world-spatial-data)

  [This](https://data.world/dgreiner/world-spatial-data/file/ne_50m_admin_0_countries.geojson) is the best dataset I found but the size of 50m scale map is about 4MB. It has details which we do not need like Income groups etc. But it is very exhaustive in terms of countries, regions, names, etc.