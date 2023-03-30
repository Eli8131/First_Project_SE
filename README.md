# First_Project_SE
First repository.
This is Eli's first repository, made to upload and share with Shane.
This repository, for now, will simply contain my first project. 
For this project, I am practicing xarray and attempting to recreate figures present in Shane's published work.
+
# File List:
1. Histogram
2. first_project_xarray
3. Histogram_v2.0
4. density_histogram.pdf
+
# Histogram
This was my first attempt at creating a density histogram for Position and Velocity, sst diurnal, and sst estimate measurements from the AWS dataset gdp_v2.00.nc. Overall data collection methods and plotting methods work (using xarray histogram), but I ran into issues regarding runtimes not being feasible while using datetime[ns] objects, causing this file to be abandoned for Histogram_v2.0. 
+
# first_project_xarray
In this file, I recreate figure 18 and the sst temperature density plot from figure 17 from Shane's "A dataset of hourly sea surface temperature from drifting buoys" using the gdp_v2.00.nc. 
+
# Histogram_v2.0
This file completes the histogram from "Histogram," using np.histogram() and converting the datetime[ns] object into a float for much faster runtimes while both plotting and collecting data. Running this notebook generates the "density_histogram.pdf" file.
