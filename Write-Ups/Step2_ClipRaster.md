# NDVI Raster Clipped to Asunción

This step involved manually clipping the full NDVI Raster using open source administrative boundary data and Python:

### Tools Used
- `geopandas`, `matplotlib`, `rasterio` in Python
- Manual clipping with shapefile from Geoboundaries Data

### Custom Python Script
[SnipRaster](../Scripts/SnipRaster.ipynb)

### Screenshots from Python Script
#### Administrative Boundaries Paraguay viewed
![Administrative Boundaries Paraguay](../Data/Paraguay_Adm_Level_1.png)
#### Administrative Boundaries Asuncion
![Administrative Boundaries Asuncion](../Data/Asuncion_Adm_Level_1.png)
#### NDVI Image Clipped to Asuncion
![NDVI Clipped to Asuncion Python](../Data/NDVI_Asuncion_Clipped.png)
#### Clipped NDVI Image Output File
![NDVI Clipped to Asuncion Python](../Data/Clipped_NDVI_Output.png)

### Notes
- Image may appear pixelated due to small clipped area
