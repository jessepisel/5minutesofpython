# Turner Sandstone Investigation
This folder contains several jupyter notebooks and an excel workbook
for reproducing results from a recent report on the Turner Sandstone in the
Powder River Basin of Wyoming.

The first jupyter notebook (turner.ipynb) and associated excel workbook are for
plotting up horizontal oil and gas well locations. 

The second jupyter notebook (Turner data munging.ipynb) and excel workbook are
used in a data munging exercise to get the data organized, cleaned, and ready
for machine learning. This notebook writes out a `csv` file that will be used
in part three.

The data is from the
Wyoming State Geological Survey [Report of Investigations 77](http://bit.ly/2IUB24J).


To run this notebook, download/clone the folder, open the notebooks and
run through all the cells in order. the first notebook will install `xlrd` and `cartopy`
which are used to read in the data and plot it on a basemap. 
![map](https://github.com/jessepisel/5minutesofpython/blob/master/Turner%20Sandstone/outputmap.jpg?raw=true "basemap")
