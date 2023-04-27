# Pedestrian accessibility indicators for the SDGs

This is the repository for the calculations behind the accessibility indicators for the SDGs by the UN Sustainable Development Center.

To read full methodology, please visit the SDG Transformation Centre website. The resulting datasets can be downloaded from the [SDG Transformation Centre Data Hub](https://sdg-transformation-center-sdsn.hub.arcgis.com/search?collection=Dataset) at [country](https://sdg-transformation-center-sdsn.hub.arcgis.com/datasets/sdsn::pedestrian-accessibility-indicators-by-country/about) or [urban center scale](https://sdg-transformation-center-sdsn.hub.arcgis.com/datasets/sdsn::pedestrian-accessibility-indicators-by-urban-center/about).

The scripts are to be followed in order. Further instructions are provided as comments within each script.

1. Global-scale raw amenities data is collected from OpenStreetMap using OsmPoisPbf and the uac_filter.txt query. Accessibility calculation are computed using the 1_calculateAccess.py script. Population grids for functional urban areas are extracted from the Global Human Settlement Layer and pre-processed using the 2_extractUA_QGIS.py script, to be run in QGIS. Accessibility per grid cell (the data used for the visuals in the app) for urban areas globally is computed using the 3_calculatedGridAccess.py script.

The scientific research behind this project is published here.

If you would like to contribute to this project, or if you have any questions about it, please contact Leonardo Nicoletti.
