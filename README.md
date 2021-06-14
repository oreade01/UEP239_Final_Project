# UEP239_Final_Project by Olivia Reader

## Abstract 

This project pinpoints the most suitable zipcodes for young families to move in the Boston Metropolitan area. The variables included in the analysis are concentrations of points of interest (schools, libraries, and farmers markets), and the percent of kindergarten enrollment.

## How to run and reproduce
  1) First, open your Windows Terminal (or preferred Powershell terminal), and clone this repository.
  2) Next, download the pandas included in the `environment.yml`document
  3) Activate the `uep239` environment.
  4) Open the `suitability.ipynb` file with Jupyter Lab
  6) Run each code in order to visualize different Boston suitability factors for young families. This code may be reproduced with other data in other cities. 

## Overview of Packages
  - `numpy`: for this project, numpy is used for basic statistical operations, and for the creation of masked arrays
  - `pandas`: a necessary package for data cleansing, filling, merges, and joins
  - `geopandas`: used to read spatial data for Boston, and visualize several maps
  - `matplotlib`: matplotlib's [colormaps](https://matplotlib.org/stable/tutorials/colors/colormaps.html) are implemented in this project for clear visuals. 
  - `contextily`: provides the basemaps used in this analysis for geographical context

## Data 
  - ```MPO_Boundaries```: This ESRI shapefile is from the Massachusetts Department of Transportation, and is a polygon feature.
  - ```Zip Codes```: This shapefile is from the United States Census Bureau; the polygons represent 5 digit zip code tabulation areas (ZCTA) boundaries in Massachusetts from 2010
  - ```School points```, ```library points```, and ```farmer market points```: all of these point data are shapefiles, and are from [MassGIS](https://www.mass.gov/orgs/massgis-bureau-of-geographic-information). The CRS of all shapefiles and basemaps used in this analysis is the Massachusetts Mainland Projection (EPSG:26986).
  - ```ACS, S1401```: 2019 American Community Survey Data from the United States Census Bureau. This data is in the csv format, and describes various measures of school enrollment. For this project, I use the column that describes the total population 3 years and older enrolled in school (kindergarten to 12th grade)


 ## Hours spent
 Approximately 25

## Citations: 
  - https://matplotlib.org/stable/tutorials/colors/colormaps.html
  - https://www.geeksforgeeks.org/python-pandas-split-strings-into-two-list-columns-using-str-split/
  - https://commonmark.org/help/
    
  - I also received help from Phil Gomez in the data lab, and all Professors offering office hours. 
