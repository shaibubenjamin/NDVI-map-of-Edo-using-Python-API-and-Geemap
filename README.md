# NDVI-map-using-Python-API-and-Geemap

![Project Banner](https://your-image-link-here.com) <!-- Optional: Add a project image or logo -->

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
- **Geospatial Boundaries**: Administrative boundary shapefiles for Edo State were obtained from reputable sources like [OpenStreetMap](https://www.openstreetmap.org/) and other publicly available geospatial datasets.

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

To run this project locally, ensure you have the following dependencies installed:

```bash
# Clone the repository
git clone https://github.com/yourusername/ndvi-analysis-edo-state.git

# Change directory to the project folder
cd ndvi-analysis-edo-state

# Create a virtual environment (optional but recommended)
python -m venv env
source env/bin/activate   # On Windows: `env\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
