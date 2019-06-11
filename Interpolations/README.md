This folder contains a jupyter notebook and a shapefile that is used to create interpolation maps of cobalt concentration in soil samples from Nunivak Island in Alaska. 

The first notebook interpolates the data with `Verde` and Green's Functions, the second notebook uses a Gaussian process in `scikit-learn` to interpolate the data, the third notebook uses `PyKriging` and ordinary kriging to interpolate the data, and the fourth notebook uses `GeostatsPy` and kriging to interpolate the data.

To run these notebooks, download the folder, open the notebook you want to work with and run through all the cells in order. It will install all the packages you need in the respective notebooks. 

![Map](https://github.com/jessepisel/5minutesofpython/blob/master/Interpolations/interpolation.JPG?raw=true "Interpolation types") 