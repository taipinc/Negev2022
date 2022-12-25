---
layout: default
title: Day 1
nav_order: 2
---

# Day 1

## QGIS, Unreal Engine, and other preperations

{:toc}

# Using Aerial Photography with QGIS

QGIS is a free and open-source cross-platform desktop geographic information system application that supports viewing, editing, printing, and analysis of geospatial data. All information and images viewed and used within QGIS is georefernced,

{: .highlight }
Install QGIS from [https://www.qgis.org/].

[https://www.qgis.org/]: https://www.qgis.org/

### Adding Layers from Public Repository

We'll add some content available on the Be'er Sheva municipal GIS website. We'll start with the short version, and then I'll go into more details that might help you in the future.

- After creating a new project, look at the the _Browser_ panel on the left side of the screen.
- Right click _ArcGIS REST Servers_ and choose _New Connection_.
- Add the following details:
  - **Name**: Be'er Sheva 2017
  - **URL**: https://gis.br7.org.il/arcgis/rest/services/basemaps/orthophoto2017/MapServer
- Double click on the new connection you created, _Be'er Sheva 2017_.
- Double click any of the layers available under that connection. That layer will be added to your project.

After completing these stems, you should have an unlimited access to the 2017 high definition orthophoto map of Be'er Sheva.
