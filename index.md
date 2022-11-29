# Trends in Carbon Monoxide and Nitrogen Dioxide as Indications of Wildfires

[Research Proposal](https://averstynen.github.io/CLIM680Project/proposal.html)

## Introduction

For my project, I will be using measurements of nitrogen dioxide and carbon monoxide obtained from a polar-orbiting satellite.
I will be analyzing daily satellite observations during the months of August, September, and October for the years 2019-2021. I will specifically be focusing on the state of California.

During this time period, there were many wildfires in California of various sizes. This project will only look at wildfires that burned over 100 hectares. This limit was set due to the constraints of the satellite grid size. Some major wildfires of note during this period were the August Complex in 2019 and the Dixie Fire in 2018. Descriptions and extents of all fires observed will be detailed in the table provided below.

The goal of this project is to observe the ability of satellite-observed nitrogen dioxide and carbon monoxide values to indicate wildfires. Another goal of this project was to see if the ratio between nitrogen dioxide and carbon monoxide can be used as an indicator of a wildfire. The motivation for this is that there is a deficit in identifying wildfires based on atmospheric constituents. This limitation is due to the fact that wildfire emissions are very similar to those produced by cities and urban areas. 

## Data

My project will focus on data obtained from the Tropospheric Pollution Monitoring Instrument (TROPOMI) which is aboard the Sentinel-5 Precursor satellite. The satellite was launched in October 2017 and has data available from August 2019 to current. The instrument tracks multiple atmospheric constituents including aerosol layer height, carbon monoxide, formaldehyde, methane, nitrogen dioxide, and sulfur dioxide. These datasets have a resolution of
5.5km x 7km.

Because of the size of the dataset, I decided to crop the dataset to only include that which covers the state of California. For this project, I also only use the nitrogen dioxide and carbon monoxide datasets from the TROPOMI satellite. These two constituents make up a large portion of the emissions from wildfires. 

## Code and Implications

### [Slicing NetCDF file](https://averstynen.github.io/CLIM680Project/CropTROPOMI.ipynb)


### [Regridding Data](https://averstynen.github.io/CLIM680Project/tropomi_regrid.ipynb)

### [Plotting](https://averstynen.github.io/CLIM680Project/ClimateData_Project.ipynb)

### Groupby

### [Subplots](https://averstynen.github.io/CLIM680Project/ClimateData_subplots.ipynb)

### [Anomalies](https://averstynen.github.io/CLIM680Project/ClimateData_Project.ipynb)

### [Functions](https://averstynen.github.io/CLIM680Project/ClimateData_Project.ipynb)

### Animations

### Linear Regression

### [Composites](https://averstynen.github.io/CLIM680Project/CLIM680_HW3_Attempt2.ipynb)

## [Results](https://averstynen.github.io/CLIM680Project/Results.html)

## Summary

[NO2 Plots](https://averstynen.github.io/CLIM680Project/NO2.html)
