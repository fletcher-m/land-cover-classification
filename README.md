# land-cover-classification
In this repository I create a land cover classification for southern Santa Barbara county.

## About
This repository contains one r-markdown document 'la_redlining.RMD' and associated HTML file that analyze the relationship between redlining districts, HOLC grades and bird sightings in Los Angeles. It includes geospatial analysis to find patterns among these three aspects. 

## Visualization
After filtering data from the United States Environmental Protection Agency's EJScreen to information about Los Angeles county, I make a plot of census block groups above the 95th percentile for wastewater discharge. I then use redlining data to make a plot of these boundaries, colored by HOLC grade. My last visual is a bar chart showing numbers of bird sightings among each HOLC grade. 

## Highlights
 
  - Data wrangling and exploration with `tidyverse`
  - Geospatial data wrangling with `sf`
  - Map making with `Tmap` and `GGPlot`
  - Creating and customizing a bar chart
  - Creating and customizing spatial plot

## Data
The data for EJscree is available from: https://www.epa.gov/ejscreen/download-ejscreen-data.
The data for redlining districts is available from: https://dsl.richmond.edu/panorama/redlining/static/downloads/geojson/CALosAngeles1939.geojson.
The data for bird sightings is available from: gbif.org
The access date for all: October 27, 2023.
