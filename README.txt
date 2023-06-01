This repository hosts code that pairs the study "Evolution of Great Salt Lake’s Exposed Lakebed (1984-2023): Variations in Sediment Composition, Water, and Vegetation from Landsat OLI and Sentinel MSI Satellite Reflectance Data" by Mark Radwin and Brenda Bowen, that is currently in review to be published under the Utah Geological Association in 2023.

The "Great_Salt_Lake_GEE_Time_Series_Product_Code.ipynb" file is a Jupyter Notebook file that was used to retrieve all satellite data for the study, to be used or adapted by others who wish to implement similar analyses.

The "GSL_Hypsometry_Interpolation_Code.ipynb" file is a Jupyter Notebook file that can be used to interpolate the Great Salt Lake hypsometry data and model water surface area and exposed lakebed area given a water elevation.
The files three .csv files pair this Notebook and are to be downloaded if you would like to implement the interpolation code. Technically, the "GSL_Area_vs_Elevation_dataframe.csv" is the only needed csv from this repository, as the other .csv's are elevation data from the Great Salt Lake which you can retrieve on your own if you have a specified timeframe or USGS waterstation data of interest.
You will need to edit the paths on the Notebook file to the correct paths of the downloaded .csv files. The output of the code are Pandas dataframes that can be exported as tables or plotted.

Please email me at markradwin@gmail.com if you have questions.
