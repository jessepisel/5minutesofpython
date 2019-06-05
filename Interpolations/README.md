This folder contains a jupyter notebook and a shapefile that is used to create interpolation maps of cobalt concentration in soil samples from Nunivak Island. More notebooks looking at different interpolation methods will be added as they are created.  

The first notebook interpolates the data with `Verde` and Green's Functions, the second notebook uses a Gaussian process in `scikit-learn` to interpolate the data, the third notebook uses `PyKriging` to interpolate the data.

To run this notebook, download the folder, open the notebook and run through all the cells in order. It will install contextily and verde which are used for creating the map, and creating the interpolation spline respectively. 

![Map](https://github.com/jessepisel/5minutesofpython/blob/master/Interpolations/samplelocations.JPG?raw=true "Sample locations") 