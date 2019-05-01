# Coloring Well Log LAS Files
This folder contains a jupyter notebook that has all the data you need to create a colored gamma-ray log for a well in Campbell County, Wyoming. The data is from the Wyoming Oil and Gas Conservation Commission for a well drilled in 2011. 

To run this notebook, download the folder, open the notebook and run through all the cells in order. It will install `lasio`, which is used for reading well log LAS files, and it will walk you through a quick data QC and how to read the files before plotting it up.

We can color in single logs for quick lithology views

![Well log](https://github.com/jessepisel/5minutesofpython/blob/master/Well%20log%20plots/davis_log.JPG?raw=true "Example well log")

Or we can plot up entire cross sections and visualize formation tops

![Cross section](https://github.com/jessepisel/5minutesofpython/blob/master/Well%20log%20plots/cross_section.JPG?raw=true "Example Cross section")

If we have directional survey data we can plot horizontal wells in a 3d view

![Horizontal well](https://github.com/jessepisel/5minutesofpython/blob/master/Well%20log%20plots/horizontalwell.JPG?raw=true "Horizontal well plot")
