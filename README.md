# SRTM Slope Classification

Automated geospatial workflow for terrain slope analysis using SRTM elevation data and Python.

## About the Project

This project was developed to automate the extraction and classification of terrain slope from SRTM Digital Elevation Model (DEM) data.

The workflow was developed in Google Colab and is designed to reduce manual processing time and generate standardized geospatial outputs.

## Workflow

The script performs the following steps:

1. Load the Area of Interest (AOI)
2. Obtain SRTM elevation data
3. Clip the DEM to the study area
4. Calculate terrain slope
5. Classify slope according to EMBRAPA classes
6. Generate contour lines
7. Export the results as geospatial files

## Slope Classification

| Class               |  Slope |
| ------------------- | -----: |
| Flat                |   0–3% |
| Slightly undulating |   3–8% |
| Undulating          |  8–20% |
| Strongly undulating | 20–45% |
| Mountainous         | 45–75% |
| Escarpment          |   >75% |

## Technologies

* Python
* Google Colab
* Google Earth Engine
* Rasterio
* GeoPandas
* NumPy
* SRTM DEM

## Outputs

The workflow generates:

* Slope raster
* Classified slope raster
* Contour lines
* Map visualization

## Objective

The main objective is to automate a repetitive GIS workflow, reducing processing time and improving the standardization of terrain analysis.

## Author

Ariane Brito

Forest Engineer | GIS | Remote Sensing | Geospatial Data
