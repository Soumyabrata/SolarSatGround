# On the Relationship Between Ground- and Satellite- Based Global Horizontal Irradiance
With the spirit of reproducible research, this repository contains all the codes required to produce the results in the manuscript:

> M. Jain\*, D. Yericherla\*, and S. Dev, On the Relationship Between Ground- and Satellite-Based Global Horizontal Irradiance, *IEEE International Geoscience and Remote Sensing Symposium (IGARSS)*, 2022. (\* Authors contributed equally.)

Please cite the above paper if you intend to use whole/part of the code. This code is only for academic and research purposes.

# Code Organization

- `data analysis.ipynb` Analysis of ground & satellite GHI data to identify the relation b/w them
- `download data.ipynb` To download reanalysis satellite data from CDS(NOAA)

## Data Files

We're using 2 sources of data in our analysis, 

1. Land Based GHI data is sourced from [Solcast website](https://solcast.com/).

...a. Register at Solcast and you will be provided some free credits.
...b. The free credits would suffice for recreating this, since analysis is done only for one city (dublin).
...c. The request would have the following City Name (Dublin here), Time Period ( 7 years here) and Parameters (GHI here).
    
2. Satellite Based GHI data is collected from [Climate Data Store (CDS) website](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels?tab=overview) by making API Calls.

