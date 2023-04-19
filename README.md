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

### All below folders/files are contained within `Harmonics_Proj` folder
`A1Plots`: This folder contains the monthly analyses of the first SST diurnal harmonic. Files are named after the month being analyzed in its figure.

`A2Plots`: This folder contains the monthly analyses of the second SST diurnal harmonic. Files are named after the month being analyzed in its figure.

`A3Plots`: This folder contains the monthly analyses of the third SST diurnal harmonic. Files are named after the month being analyzed in its figure.

`Data Collection`: This folder contains the Jupyter notebooks used to build the xarray datasets plotted in the harmonics figures. The following three notebooks are contained within this folder:

`harmonicsA1_collection.ipynb`: This notebook is used to analyze the first harmonic data and generates a .txt file for the total analysis of the first harmonic and for each monthly analysis.

`harmonicsA2_collection.ipynb`: This notebook is used to analyze the second harmonic data and generates a .txt file for the total analysis of the second harmonic and for each monthly analysis.

`harmonicsA3_collection.ipynb`: This notebook is used to analyze the third harmonic data and generates a .txt file for the total analysis of the third harmonic and for each monthly analysis.

`Plotting`: This folder contains the three files used to create the figures for the total and monthly analyses for each harmonic. The following three notebooks are contained within this folder:

`HarmonicsA1.ipynb`: This notebook loads the .txt files saved by `harmonicsA1_collection.ipynb` to create figures visualizing the first harmonic amplitude. This notebook is used to generate all files in `A1Plots` and `A1.png` in the folder 'tot_amplitude_plots'.

`HarmonicsA2.ipynb`: This notebook loads the .txt files saved by `harmonicsA2_collection.ipynb` to create figures visualizing the second harmonic amplitude. This notebook is used to generate all files in `A2Plots` and `A2Plot.png` in the folder 'tot_amplitude_plots'.

`HarmonicsA3.ipynb`: This notebook loads the .txt files saved by `harmonicsA3_collection.ipynb` to create figures visualizing the third harmonic amplitude. This notebook is used to generate all files in `A3Plots` and `A3Plot.png` in the folder 'tot_amplitude_plots'.

`animation.ipynb`: This notebook loads all of the monthly analyses of a selected amplitude (a set of .png files in a folder) and outputs an animated .gif file. This notebook was used to create `A1animation.gif`, `A2animation.gif`, and `A3animation.gif` in the `amplitude_animated` folder.

`amplitude_animated`: This folder contains all of the animated figures which are .gifs of all of the monthly analyses figures of a certain harmonic amplitude. The following files are contained in this folder:

`A1animation.gif`: Animated .gif of the first harmonic monthly analyses.

`A2animation.gif`: Animated .gif of the second harmonic monthly analyses.

`A3animation.gif`: Animated .gif of the third harmonic monthly analyses.
