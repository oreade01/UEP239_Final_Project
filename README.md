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
  - MPO_Boundaries: shapefile from MassDOT
  - Zip Code boundaries: shapefile from Census Bureau
  - School points, library points, and farmer market points: shapefiles from MassGIS
  - ACS data: 2019 American Community Survey Data

 Python packages used, describe in the environment.yml file

 Hours spent: Approximately 15

## Citations: 
    <https://matplotlib.org/stable/tutorials/colors/colormaps.html>
    <https://www.geeksforgeeks.org/python-pandas-split-strings-into-two-list-columns-using-str-split/>
    
     I also received help from Phil Gomez in the data lab, and all Professors offering office hours. 
