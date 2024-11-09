# RBF
This is the python code to perform Rapid Building Backdating Footprint method. 

To run this code, you need to install several libraries using pip or conda, including rasterio, geopandas, numpy, shapely, and sklearn. 
You need contemporary building data, validation dataset, and built-up mask layers. 

Building dataset them could be obtained from:
1. OSM: https://github.com/giscience/oshdb
2. Microsofot building footprint: https://github.com/microsoft/GlobalMLBuildingFootprints/tree/main/examples

If you do not have your own high-resolution built-up masks, you could used several global built-up layer from:
1. Global Urban Footprint: https://geoservice.dlr.de/web/maps/eoc:guf:3857
2. Global artificial impervious area: https://data-starcloud.pcl.ac.cn/
3. Global impervious surface area: http://irsip.whu.edu.cn/resources/dataweb.php
4. GHS-BUILT-S: https://human-settlement.emergency.copernicus.eu/download.php

Alternatively, you could use the land cover maps and derived the built-up information. Global land cover product could be obtained from:
1. Near real-time dynamic world: https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1
2. Esri Annual Land Cover: https://gee-community-catalog.org/projects/S2TSLULC/
3. Copernicus Dynamic Land Cover: https://land.copernicus.eu/en/products/global-dynamic-land-cover

Considering rapid development in remote sensing community, other data might be available in the future. You could easily find at: https://gee-community-catalog.org/

