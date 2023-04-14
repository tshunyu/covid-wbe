# covid-wbe project

## Dependencies
1. geopandas
1. matplotlib
1. numpy
1. pandas
1. pytorch
1. python 3.10
1. scienceplots

## Raw Data
1. NWSS_Concentration_Data.csv, downloaded from CDC website on Dec 21, 2022
1. NWSS_Metric_Data.csv, downloaded from CDC website on Dec 21, 2022
1. wastwater_by_county.csv, downloaded from Biobot's Github repository on Dec 21, 2022
1. cases_by_county.csv, downloaded from Biobot's Github repository on Dec 21, 2022

## Processed Data
1. compiled_data.csv. This is the studied dataset compiled from the above-mentioned four raw datasets.
2. county_df.csv. This is an intermediate dataframe used to prorate reported cases to the WWTPs of each county.
3. results.csv. This is the dataset with the optimized parameters for each studied WWTP. 

## Jupyter Notebooks
1. 1-Data_Compilation.ipynb. This notebook is used to generate compiled_data.csv and county_df.csv.
2. 2-Pytorch_Optimization.ipynb. This notebook is used to generate results.csv. 
3. 3-Geopandas_plot.ipynb. This notebook is used to generate Fig. 1 - the spatial visualization of the studied counties. 
4. 4-Raincloud_plot.ipynb. This notebook is used to generate Fig. 8 and 9 - the raincloud plots to study the confounding factors. 
5. 5-Simulation_Visualization.ipynb. This notebook is used to generate Fig. 3, 6 and 7 - visualization of hypothetic and real-world simulation results. 
