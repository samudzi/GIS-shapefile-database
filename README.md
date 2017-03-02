# Mapping Public Health
This repository contains a collection of GeoJSON and shapefile data for creating maps to support public health efforts.  The data has been obtained from a wide range of sources, including various US Federal gov't departments (Census Bureau, EPA, CMS, BLS) as well as state, county, and municipal governments.

Currently, GIS data is currently spread out across the web.  For people seeking to apply this data for public health analysis, data acquisition - rather than analysis and presentation - is a tenuous and time consuming process.  The goal of this repository is to centralize GIS elements that are commonly used for public health analysis to make it easier for developers and other organizations to do the actual work of visualizing and solving the major public health issues of today.


## Contributing

Please read [CONTRIBUTING.md] for details on how you can contribute, and the process for submitting pull requests to us.


## Getting Started

If you are new to GIS or building interactive web-based maps, here are some resources for getting started

### Prerequisites

#### CSV manipulation tools

Sadly, some of the key datasets are only available as CSV, so you will need to be able to transform as necessary and save as DBF or Shapefile format

#### Shapefile manipulation tools

Some of the more popular options are:

ArcGIS (paid tool) - https://www.arcgis.com/features/index.html

QGIS (free, available for Windows, Linux, MacOSX and more) - http://www.qgis.org/en/site/forusers/download.html

Mapbox (Tilemill, Mapbox Studio Classic, and cloud-based tools) - https://www.mapbox.com/ , https://tilemill-project.github.io/tilemill/ 

#### Mapping libraries and tools for generating rich web-based maps

Mapbox GL - https://github.com/mapbox/mapbox-gl-js

Leaflet - https://github.com/Leaflet/Leaflet

R interface to Leaflet (for big data on maps, or interactive maps with R data) - https://github.com/rstudio/leaflet

For topographic maps - https://github.com/topojson/topojson

Streaming parser (great tool for quickly checking contents of a given shapefile) - https://github.com/mbostock/shapefile

Polymaps - (https://github.com/jasondavies/polymaps)

#### Map servers

MapServer- https://github.com/mapserver/mapserver


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

