# Agri-Sentinel Monitor: Vegetation Health Analysis

This project analyzes Sentinel-2 satellite imagery to monitor agricultural vegetation health using indices like NDVI (Normalized Difference Vegetation Index).

## Project Goals
- Retrieve Sentinel-2 optical data for a specific area of interest (AOI).
- Process satellite imagery to correct for atmospheric effects (if needed) and cloud cover.
- Calculate Vegetation Indices (NDVI, NDMI).
- Visualize crop health changes over time.

## Data Source
- **Copernicus Open Access Hub**: Sentinel-2 MSI (MultiSpectral Instrument) data.

## Structure
- `data/`: Raw and processed geospatial data (GeoTIFFs, Shapefiles).
- `notebooks/`: Jupyter notebooks for exploratory data analysis and visualization.
- `src/`: Python scripts for data fetching and processing modules.

## Setup
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Create a `.env` file with your Copernicus credentials if using `sentinelsat`.
