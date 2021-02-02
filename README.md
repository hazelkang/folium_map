# folium_map
creating maps with folium (via python)

[Map Visualization]

Using folium library (Python), visualized Air Pollution Stations in South Korea, with the latitude/longitude info available below:
https://github.com/southkorea/southkorea-maps/blob/master/kostat/2013/json/skorea_municipalities_geo.json

-Air pollution (PM10) level & air pollution monitoring station location data was downloaded from AirKorea (https://www.airkorea.or.kr/index)

Conducted the following map visualizations:
  1) Choropleth of each location's average PM10 levels (average of Oct-Dec through years of 2010-2016) with folium.CircleMarker 
  2) Location of each air pollution monitoring station (coloring the district in one color) 

-Manually compiled info on addresses of stations' latitude/longitude 
-Conducted min/max stardardization of PM10 levels to visualize the colors better


