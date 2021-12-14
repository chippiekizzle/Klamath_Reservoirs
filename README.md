# Klamath Reservoirs
Data analysis of algal blooms in two Klamath Reservoirs (Copco & Iron Gate) from 2015 - 2020 using Sentinel-2 imagery. 
Four spectral indices (NDVI, NDCI, B8AB4, B3B2) applied to Sentinel-2 imagery were compared to in situ chlorophyll-a and Microcystin data. 

## Google Earth Engine Scripts
* Download .csv files of the four spectral indices from Google Earth Engine using [this code](https://code.earthengine.google.com/2a174867fc402f1647e2e9e228d2644e). This is the bulk of the analysis. 

* [This Google Earth Engine code](https://code.earthengine.google.com/641db50ef7baf4ac53c6eadb39487cb6) will plot full time series charts of the 3 sample locations of this study without regard to in situ sampling days. These are atmospherically corrected. This is mainly for comparison and display, rather than analysis. 

## R Scripts
* Use the Regression_Chla_GEE R code for analysis of Sentinel-2 imagery based on 4 spectral indices and in situ chlorophyll-a data.

* Use the Regression_Microcystin R code to analyze toxins data from Copco & Iron Gate Reservoirs (2015-2020). 

## In Situ Data
* Chlorophyll-a and Microcystin in situ data are available on the [PacifiCorp website](https://www.pacificorp.com/energy/hydro/klamath-river/water-quality.html). 

