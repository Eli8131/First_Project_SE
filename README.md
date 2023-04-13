# First_Project_SE
This is Eli's first repository, made to upload and share with Shane.
This repository, for now, will simply contain my first project. 
For this project, I am practicing xarray and attempting to recreate figures present in Shane's published work.

# File List:
`Histogram.ipynb`: This notebook is a partially-functioning first attempt at creating 'density_histogram.pdf'. Ran into runtime issues using datetime[ns] datatype, so I retried in 'Histogram_v2.0'

`first_project_xarray.ipynb`: This notebook recreates figure 18 and the sst density map from figure 17 in "A dataset of hourly sea surface temperature from drifting buoys" using the gdp_v2.00.nc. 

`Histogram_v2.0.ipynb`: This notebook completes the histogram from figure 17 in "A dataset of hourly sea surface temperature from drifting buoys" by converting the datetime[ns] object to float64 and generates the figure `density_histogram.pdf`.

`fig_17_density.ipynb`: This notebook is a cleaned up version of the code in `first_project_xarray.ipynb` for generating figure 17. Each figure contained in figure 17 has its own pdf file generated in this notebook.

`fig_18_sst.ipynb`: This notebook is a cleaned up version of the code in `first_project_xarray.ipynb` and `Histogram_v2.0.ipynb` for generating figure 18. Each figure contained in figure 18 has its own pdf file generated in this notebook.

`Harmonics_Proj`: This folder contains all the files used to recreate the mean diurnal cycle harmonic amplitude and phase figures on slide 40 of *elipot-aoml2022.pdf* presentation.

### All below folders/files are contained within 'Harmonics_Proj' folder
