# SQL Queries from CSV File: Zonal Statistics Export

After analysis in QGIS, the table was exported to CSV for use in further processing and SQL classification.

### Tools Used
1. SQLite3 and Pandas in Python
2. QGIS to export CSV file

### Python Scripts
[SQL Queries](../Scripts/SQLqueries.ipynb)

### Screenshots
- [Zones Rearranged by mean NDVI](../Screenshots/SQL_Low_to_High.png)
- [Zones Classified into 3 groups](../Screenshots/SQL_Classification.png)

### Notes
- Classification is arbitrary and relative to the levels of the input data.
- In reality these are all low NDVI values because Asuncion is mostly concrete and buildings and not trees.
