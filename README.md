# Mapping Public Health
This repository contains a collection of GeoJSON and shapefile data for creating maps to support public health efforts.  The data has been obtained from a wide range of sources, including various US Federal gov't departments (Census Bureau, EPA, CMS, BLS) as well as state, county, and municipal governments.

Currently, GIS data is currently spread out across the web.  For people seeking to apply this data for public health analysis, data acquisition is a tenuous and time consuming process.  The goal of this repository is to centralize GIS elements that are commonly used for public health analysis to make it easier for developers and other organizations to do the actual work of visualizing and solving the major public health issues of today.


## Contributing

The data is organized by granularity (national, regional, state, county, or city) and then by year of publication.  For example, for a dataset on 2015 Medicare utilization by county within the state of Nevada:

```
/Nevada/2015/Medicare_utilization.shp
```

Other than a descriptive name for the dataset, there is no set naming convention.

The only requirement for contributing is that the data must reflect a good faith effort at accuracy and completeness.  So for example, a dataset titled "US county lines" that is missing counties would not be acceptable, since a complete dataset is easily available.  You must also have proper license to share any datasets you intend to contribute.


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

