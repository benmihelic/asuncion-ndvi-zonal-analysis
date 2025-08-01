# NDVI Vegetation Analysis – Asunción, Paraguay

This project analyzes vegetation coverage across urban zones in **Asunción, Paraguay** using **NDVI (Normalized Difference Vegetation Index)** derived from Landsat 8-9 satellite imagery. The goal was to assess green space distribution by manually delineated zones and calculate per-zone vegetation indices.

---

## Objectives

- Generate NDVI raster imagery from Landsat 9 satellite data using Python
- Clip raster to the Asunción area using polygon boundaries
- Manually digitize urban zones based on reference imagery using QGIS
- Use QGIS's Zonal Statistics plugin to extract NDVI metrics by zone
- Style zones based on NDVI values and create a professional printable map
- Export zonal statistics as CSV file and use SQL to classify zones by vegetation density

---

## Tools & Technologies

- **Python**: `rasterio`, `geopandas`, `matplotlib`
- **QGIS**: manual vector digitizing, styling, labeling, and layout
- **Zonal Statistics Plugin**: mean, min, max, stddev NDVI per zone
- **SQL**: select, group, order
- **Data Sources**:
  - Sentinel-2 NDVI bands (pre-calculated)
  - GeoBoundary & OpenStreetMap boundary data
  - Manually digitized zone reference from city map (PDF to polygon tracing)

---

## Outputs

- [**NDVI raster** calculated from Landsat 9 sattelite images](Scripts/CreateNDVIRaster.ipynb)
- [**Clippled NDVI raster** using administrative boundaries](Scripts/SnipRaster.ipynb)
- [**Custom polygon zones** digitized manually from city map](Data/CIUDAD_DE_ASUNCION_CATASTRAL_2022.pdf)
- [CSV file of zonal statistics with NDVI **mean, min, max, and standard deviation**](Outputs/Zonal_Statistics.csv)
- [Styled vector map with labels and graduated colors](Outputs/Mean_NDVI_by_Zone.png)
- [Write up of steps](Write-Up)

---

## Skills Demonstrated

- Raster clipping and reprojection in Python
- Vector layer creation from scratch in QGIS
- Spatial data alignment and styling
- Statistical analysis with raster zonal operations
- Database manipulation with SQL and Python
- Layout and design of printable geospatial maps

---

## Attribution

- Satellite imagery: [Landsat 8-9 Data](https://earthexplorer.usgs.gov/)
- Boundary data: [GeoBoundaries](https://www.geoboundaries.org/simplifiedDownloads.html), [OpenStreetMap](https://www.openstreetmap.org), [Municipality of Asuncion](https://www.asuncion.gov.py/)
- Software: [QGIS](https://qgis.org), Python

---

> **Author**: Ben Mihelic – July 2025  
> [benmihelic30@gmail.com](mailto:benmihelic30@gmail.com)
