# Step 2: NDVI Raster Clipped to Asunción

This step involved manually clipping the full NDVI Raster using open source administrative boundary data and Python:

### Tools/Data Used
- `geopandas`, `matplotlib`, `rasterio` in Python
- Manual clipping with shapefile from Geoboundaries Data

### Custom Python Script
[SnipRaster](../Scripts/SnipRaster.ipynb)

### Screenshots from Python Script
#### Original Shapefile of Administrative Boundaries
![Administrative Boundaries Paraguay](../Screenshots/Paraguay_Adm_Level_1.png)
#### Filtered for Asuncion Polygon
![Administrative Boundaries Asuncion](../Screenshots/Asuncion_Adm_Level_1.png)
#### NDVI Image Clipped to Asuncion Polygon
![NDVI Clipped to Asuncion Python](../Screenshots/NDVI_Asuncion_Clipped.png)
### Clipped NDVI Image Output File
![NDVI Clipped to Asuncion Python](../Screenshots/Clipped_NDVI_Output.png)

### Notes
- Image may appear pixelated due to small clipped area
