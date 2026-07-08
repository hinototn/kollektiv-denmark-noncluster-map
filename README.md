# Kollektiver in Copenhagen

This is an interactive map of kollektiver in Copenhagen.

I made this map to make the kollektiv landscape easier to see, explore, and share. A spreadsheet can show the data, but a map shows the pattern. It makes it easier to see where kollektiver are clustered, how they relate to the city, and how collective housing exists as part of Copenhagen’s everyday urban fabric.

The map was created for sharing at the Communal Studies Conference in Germany, July 8-11.


## What the map does

The map shows kollektiv locations as clickable points. Users can zoom in and out, move around the city, and click each point to see basic information.

The map is intentionally simple. I wanted it to be easy to use, easy to present, and easy to share.


## Why this matters

Kollektiver are often talked about as social or architectural experiments, but they are also spatial - they exist in specific neighborhoods, buildings, and urban contexts.

Mapping them helps make that geography visible.

This map is a starting point for thinking about collective living through space: where it happens, how dense it is, and how it connects to the larger city.


## Data

The map uses a CSV of kollektiv locations. The data was cleaned and geocoded before being added to QGIS.

For privacy, the public map only shows basic location and descriptive information. Sensitive survey fields were not included.


## Tools

This map was made with:

- QGIS
- qgis2web
- Leaflet
- GitHub Pages

QGIS was used to prepare and style the data. qgis2web exported the map as a web map. GitHub Pages hosts the final interactive version.


## Status

This is a working public version of the map. It can be updated as more kollektiv data becomes available or if locations need to be corrected, removed, or generalized.
