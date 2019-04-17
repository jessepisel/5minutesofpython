# Reprojecting Soil Geochemistry Data
This folder contains a jupyter notebook and two `.csv` files for an introduction to reprojecting 
a GeoDataFrame from raw tabular data. This notebook opens the `.csv` files and extracts
the latitude and longitude of each point. It then takes the points and creates a 
`GeoDataFrame` using `geopandas`. It then merges geochemistry data with the `GeoDataFrame` and reprojects
it into two different projections before plotting it on a basemap.
![Basemap](https://github.com/jessepisel/5minutesofpython/blob/master/Reprojections/basemap.JPG?raw=true "Basemap with cobalt concentrations")

To run this notebook, download/clone the folder, open the notebook and run through all the cells in order.