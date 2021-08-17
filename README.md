# MAST30034 Project 1 - Quantitative Analysis
- Student Name: Sanqiang Jiang
- Student ID: 956163
- Due Date: Friday 13th of August 11:59:00 am (AEST).
- Report Link: _Insert Report Link if applicable_

# Dependencies
- Language: _i.e Python 3.8.3 and/or R 4.05_
- Packages / Libraries:pandas,sklearn,folium,numpy,warnings,seaborn,matplotlib.pyplot,matplotlib.mlab.

# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- External dataset Weather: https://www.ncei.noaa.gov/orders/cdo/2682845.csv


# Directory
_Change this to fit your needs when you have started the project._
- `raw_data`: Contains all the raw data files. You may add this folder to `.gitignore` if your files are too large, but you **must** provide code to automatically download or links so that we may manually download them. 
-raw_data/yellow: "the new folder need to be created before download the TLC file"
-raw_data/taxi_zones: "files for folium and geopandas"
- `preprocessed_data`: Contains all the preprocessed data files. You may add this folder to `.gitignore` if your files are too large, but your script should automaticaally generate files here given the correct dataset in `raw_data`.
- `plots`: Output and save all your figures here.
- `code`: Keep all notebooks and scripts in this folder. Ensure that you have notebooks for each _stage_ of code. Here's an example:
    - Download.ipynb for "download the TLC files"
    - data_cleaning.ipynb for "Preprocessing" and/or "Exploratory Data Analysis".
    - weather.ipynb for "read in weather csv file and preprocessing, combine weather data with cleaned TLC feather file."
    - Demand.ipynb for "Analysis and visualisation of what effect demand of yellow taxi"
    - Tips.ipynb for "Analysis and visualisation of what effect the tips"
    - Geospatial.ipynb for "Geospatial Visualisation"
    - modeling.ipynb for "Statistical Modelling".
- `deprecated`: A folder to store "old code" that **you do not use anymore** or code that you experimented with, but decided to not go ahead. This is useful in case you ever need to come back to an older iteration of code or to express your other approaches to the problem.

# Other
-the auto saveing of Geospatial.ipynb may not avaliable after running all code in this file.
-most of the plot are not shown in the report is shown here.
-there exit some plot is saved by screenshot
-the external dataset weather is modified, please use the csv file included in the raw_data.
