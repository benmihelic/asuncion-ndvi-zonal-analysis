# Step 6: SQL Queries from Zonal Statistics CSV

After analysis in QGIS, the table was exported to CSV for use in further processing and SQL classification.

### Tools Used
1. SQLite3 and Pandas in Python
2. Zonal Statistics CSV file exported from QGIS

### Python Scripts
[SQL Queries](../Scripts/SQLqueries.ipynb)

### Screenshots
#### Styled Map By Zone Number
![Styled_Map_by_Zone_Number](../Screenshots/Styled_Zones_by_Zone_Number.png)
#### Zones Rearranged by Mean NDVI
![Zones Rearranged by mean NDVI](../Screenshots/SQL_Low_to_High.png)
#### Zones Classified into 3 Groups
![Zones Classified into 3 groups](../Screenshots/SQL_Classification.png)

### Notes
- Classification is arbitrary and relative to the levels of the input data.
- In reality these are all low NDVI values because Asuncion is mostly concrete and buildings and not trees.
