# Project-2-Wildfire-mapping

Interactive global wildfire mapping and analysis of NASA-Data using Python.

## Project Description

This project looks at global wildfire patterns using recent spatial data from NASA FIRMS (2026) and interactive mapping methods in Python. The goal is to visualize wildfire occurrence and explore the attributes: Brightness, Frp and Confidence. With this information, the wildfires can be compared easily and quickly on a rather general overview level.

## Repository Structure

```text
notebooks/   -> The Jupyter notebooks with the analysis and visualization
outputs/     -> exported maps
```

## Data Sources

The project uses open spatial datasets from the following sources:

- NASA FIRMS wildfire data:
  https://firms.modaps.eosdis.nasa.gov/data/active_fire/modis-c6.1/csv/MODIS_C6_1_Global_24h.csv 

- Additional basemap or geographic data:
  The interactive map uses the "CartoDB dark_matter" basemap provided through the Folium library.

Data are accessed directly from online sources (URL) and are therefore not stored in this repository.

## Requirements

The project was developed using Jupyter Notebook.

Required Python libraries include:

- pandas
- geopandas
- folium

Install required libraries with:

```bash
pip install pandas geopandas folium
```

## Setup Instructions

1. Clone this repository:

```bash
git clone https://github.com/lucyangelillo/Project-2-Wildfire-mapping.git
```

2. Open the project folder.

3. Install the required packages:

```bash
pip install pandas geopandas folium
```
4. Start JupyterLab or Jupyter Notebook.

5. Open and run the notebook inside the `notebooks/` -> "Wildfire_mapping" folder from top to bottom.

## Execution Order

1. Open the wildfire mapping notebook in the `notebooks/` folder.
2. Run all notebook cells in order from top to bottom.

The notebook performs:

- data loading from NASA FIRMS
- cleaning and selecting relevant data
- spatial data conversion using GeoPandas
- wildfire classification
- interactive wildfire map creation using Folium

Final interactive maps are displayed directly inside the notebook.

## Output

The project produces:

- interactive wildfire maps with different amount of informations
- spatial visualizations
- wildfire distribution analysis

## Author

Lucy Lu Angelillo, 
22.05.2026