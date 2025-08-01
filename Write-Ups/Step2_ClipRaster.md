# NDVI Raster Clipped to Asunción

This step involved manually clipping the full NDVI Raster using open source administrative boundary data and Python:

### Tools Used
- `geopandas`, `matplotlib`, `rasterio`
- Manual clipping with shapefile from Geoboundaries Data

### Custom Python Script
[SnipRaster](Scripts/SnipRaster.ipynb)

### Screenshots From Python Script
- [Administrative Boundaries Paraguay](../Data/Paraguay_Adm_Level_1.png)
- [Administrative Boundaries Asuncion](../Data/Asuncion_Adm_Level_1.png)
- [NDVI Clipped to Asuncion](../NDVI_Asuncion_Clipped.png)

### Notes
- Image may appear pixelated due to small clipped area
- Data properly aligned using consistent CRS
