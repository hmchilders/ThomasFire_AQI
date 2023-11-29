# Impact of the 2017 Thomas Fire

Author: Heather Childers

## About this Notebook:
The purpose of this exercise is to explore the impact of the 2017 Thomas fire on Santa Barbara County air quality and land cover. We'll analyze the impact on air quality by plotting the daily and 5-day rolling average values of the air quality index for 2017 and 2018 to compare the AQI during the Thomas fire to the usual AQI for the area. We'll explore the land cover change by using a false color image of Santa Barbara County and comparing it with the fire scar from the Thomas Fire.

Some highlights of this analysis include:
- Fetching data from an online repository
- Data wrangling
- Time Series analysis
- Creating line plots with a legend
- Creating a false color image
- Visulaizing raster data

## About the data:
We'll be using the following Datasets for this analysis:

1. Air Quality Index (AQI) data from the US Environmental Protection Agency to visualize the impact on the AQI of the 2017 Thomas Fire in Santa Barbara County.
The data can be accesses here: “AirData Website File Download Page.” EPA, Environmental Protection Agency, aqs.epa.gov/aqsweb/airdata/download_files.html#AQI. Accessed 28 Nov. 2023. 

2. A simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmosperically corrected surface reflectance data, collected by the Landsat 8 satellite.
The data can be accessed in the data folder of this repository. More info can be found here: “Microsoft Planetary Computer.” Planetary Computer, planetarycomputer.microsoft.com/dataset/landsat-c2-l2. Accessed 28 Nov. 2023.  

3. A shapefile of fire perimeters in California during 2017
The data can be accessed here: “California Fire Perimeters (All).” California State Geoportal, California Department of Forestry and Fire Protection, gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about. Accessed 28 Nov. 2023. 