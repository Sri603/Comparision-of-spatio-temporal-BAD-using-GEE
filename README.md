# Comparision-of-spatio-temporal-BAD-using-GEE
# Overview
This project focuses on comparing the spatio-temporal distribution of burned area (BA) estimates derived from multi-annual global datasets, including MODIS (MCD64A1) and FIRMS. Using Google Earth Engine (GEE) and Python the project aims to analyze the spatial and temporal dynamics of burned areas across Australia. This repository provides all the necessary resources to replicate the analysis and results.
# Objectives
The primary goals of this project are:

**Dataset Comparison**: Evaluate spatial and temporal discrepancies between MCD64 and VIIRS datasets.
**Environmental Impact Assessment**: Analyze how land use, vegetation, and environmental factors (e.g., Forest loss, land surface temperature) influence burned areas.
**Visualization and Interpretation**: Generate maps, graphs, and charts for better understanding of fire patterns across Australia.
**Scalability**: Leverage GEE’s cloud-based processing for scalable and automated analysis.
**Machine Learning**: Use Gradient Boost Tree (GBT) classifiers to enhance classification accuracy.
# Dataset and Tools
Datasets
MODIS (MCD64A1): Burned area product at 500m resolution.
FIRMS: Active fire and burned area product.
MODIS LULC: Land Use and Land Cover.
MODIS NDVI: Normalized Difference Vegetation Index for pre- and post-fire assessment.
Hansen Forest Cover: Deforestation data.
Other Ancillary Data: Precipitation, and elevation.
Tools and Libraries
Google Earth Engine (GEE): Cloud-based geospatial processing platform.
Python Libraries: earthengine-api, numpy, pandas, matplotlib, geopandas, scikit-learn, seaborn

# Methodology
Data Collection:

Access multi-annual global datasets via GEE.
Filter and clip datasets to the region of interest (ROI): Australia.

Burned Area Classification:

Apply a burn mask to isolate burned areas using threshold values.
Train and evaluate a Gradient Boost Tree classifier with predictor variables such as NDVI, Forest loss and LULC.

Spatial Analysis:

Overlay burned area maps with land use data to assess impacts on different land cover types.

Temporal Analysis:

Create time series of NDVI patterns to monitor vegetation recovery post-fire.
Assess burned area trends over the period 2019–2023.

Visualization:

Generate thematic maps, time series plots, and interactive dashboards.
# GEE Codes 
**Comparision of Global Burned Area Products:** 
https://code.earthengine.google.com/53a26f11fd0643b974c2cf68a63129ab

You can get the full script of GEE in the respected folders above.
# Outputs
You can find the outputs in the G-Drive Folder where we have exported the data from GEE directly.
link for G-Drive : https://drive.google.com/drive/folders/12pYmEQyXNLtNUiMee_030KDD5Hod12tu?usp=sharing

# Geoinformatics Project website
This website has been developed to provide an overview of the project. Additionally, a dedicated map page has been included to visualize various layers such as burned area polygons, Forest Loss and LST-land surface temperature.

You can access the website using the following link: https://serene-semolina-7a60e7.netlify.app/
