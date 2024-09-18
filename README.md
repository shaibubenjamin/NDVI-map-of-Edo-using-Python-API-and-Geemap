# NDVI-map-using-Python-API-and-Geemap

![NDVI-map-of-Edo-state](https://github.com/shaibubenjamin/NDVI-map-of-Edo-using-Python-API-and-Geemap/blob/388ca70dd62aa67572d286c886c859c5ca00040c/NDVI%20of%20Edo%20state.png) <!-- Optional: Add a project image or logo -->

## Overview

This project focuses on analyzing the **Normalized Difference Vegetation Index (NDVI)** for Edo State, Nigeria, using geospatial data and satellite imagery. The analysis provides insights into vegetation health and coverage, enabling better environmental and agricultural planning.

## Table of Contents

1. [Project Objective](#project-objective)
2. [Data Sources](#data-sources)
3. [Methodology](#methodology)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [Technologies Used](#technologies-used)
8. [Contributors](#contributors)
9. [License](#license)

## Project Objective

The objective of this project is to utilize NDVI for monitoring vegetation health across Edo State. This index helps in understanding the state of the environment and identifying regions that may need intervention for conservation or agriculture optimization.

## Data Sources

- **Satellite Imagery**: The primary data source for this project is satellite imagery from platforms such as [Google Earth Engine](https://earthengine.google.com/).
- **Geospatial Boundaries**: Administrative boundary shapefiles for Edo State were obtained from reputable sources like [GADM](https://gadm.org/) and other publicly available geospatial datasets.

## Methodology

1. **Data Preprocessing**: Preprocessing of satellite images and boundary data to extract the Edo State region.
2. **NDVI Calculation**: NDVI is calculated from satellite images using the formula:
   \[
   NDVI = \frac{NIR - RED}{NIR + RED}
   \]
   where NIR is the near-infrared band and RED is the red band of the satellite data.
3. **Visualization**: Results are visualized on an interactive map using libraries like **Folium** or **Matplotlib**.
4. **Analysis**: Insights are drawn based on the spatial distribution of vegetation health.

## Installation

Kind follow the step by step process in the code to run similar projects

## Results

### NDVI Maps

The generated NDVI maps showcase different vegetation health across Edo State. Some key findings include:

- **High NDVI Values**: Regions with dense vegetation, including forests and farmlands, have higher NDVI values, indicating healthier vegetation.
- **Low NDVI Values**: Urban areas and regions with less vegetation exhibit lower NDVI values, signaling reduced or stressed vegetation.
- **Seasonal Variation**: The NDVI values also reflect seasonal changes, with greener landscapes during the wet season and lower vegetation health during the dry season.

### Analysis Insights

- **Agricultural Areas**: The NDVI maps help identify regions with healthy crops, which can be useful for agricultural planning.
- **Environmental Monitoring**: Areas with declining NDVI values may require environmental protection measures, such as reforestation or sustainable farming techniques.

## Technologies Used

- **Python**: Core language used for data analysis and geospatial processing.
- **Google Collab**: For organizing and executing code in a readable format.
- **Google Earth Engine**: For accessing and processing satellite imagery.
- **Geopandas**: For handling geospatial data efficiently.
- **Matplotlib / Folium**: For data visualization of NDVI results.
- **Shapely**: For geometric operations related to spatial data.

## Contributors

- **Shaibu Benjamin Ojoka** - [LinkedIn](https://www.linkedin.com/in/shaibu-benjamin-ojoka/) | [Twitter](https://twitter.com/username)

