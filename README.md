# Land Cover Classification in the Santa Barbara Region
In this repository I create a land cover classification for southern Santa Barbara county.

## About
This repository contains one r-markdown document 'sb_land_cover.RMD' and associated HTML file that analyze data collected from collected from the landsat5 satellite and use this to create a land cover classification map for Santa Barbara.

## Visualization
After exploratory plotting of all bands collected from the landsat5 satellite, I then crop to region of Southern Santa Barbara. After using training data and reflectance data, a decision tree is created. This decision tree is then applied to the Southern Santa Barbara county region to develop a land cover classification map. 

## Highlights
 
  - Raster manipulation with `terra`
  - Geospatial data wrangling with `sf` 
  - Making a decision tree with `rpart`
  - Visualizing land cover with `Tmap`

## Data
The data from landsat5 can be found here: https://www.usgs.gov/landsat-missions/landsat-5 
The data for the souther Santa Barbara County region and training data for the decision tree can be found in the 'data' folder within this repository. All data accessed on November 28, 2023

