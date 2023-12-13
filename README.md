
## Title: Analysis of Change in Biodiversity Intactness Index from 2017 to 2020 in the Phoenix area
#### 🤠 Author: Flora Hamilton | floraham@github.io 

## Objective: 
This project assesses changes in biodiversity intactness in Phoenix from 2017 to 2020 using the Biodiversity Intactness Index (BII) from the Microsoft Planetary Computer. By comparing BII values between 2017 and 2020, we identified areas of change. Shapefiles from the US Census Bureau defined the study area within Phoenix, Arizona.

### Analysis highlights:
1) Upload Phoenix .shp
2) Upload rasters with BII data for 2017 and 2020 from the MPC
3) Clip the rasters to Phoenix gemoetry
4) Calculate % BII change from 2017 to 2020
5) Visualize the areas changed between 2017 and 2020. 


#### 📦 Repo Link: https://github.com/floraham/biodiv-index-phx
This Github repository contains a Python (.ipynb) notebook conducting an analysis of change in Biodiversity Intactness Index from 2017 to 2020 in the Phoenix area. We use two datasets to conduct this analysis. BII data is part of the MPC STAC catalog, and Phoenix shapefiles were sourced from Census County Subdivision shapefiles for Arizona. 


#### 🔎 Dataset descriptions:

##### BII data
- This dataset is part of the MPC STAC catalog. We access the `io-biodiversity` collection and look for the 2017 and 2020 rasters covering Phoenix subdivision. The following coordinates for a bounding box define our search: [-112.826843, 32.974108, -111.184387, 33.863574]

##### Phoenix subdivision shapefile: 
- The Phoenix subdivision polygon is found in the Census County Subdivision shapefiles for Arizona:
https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions


### Repository Structure 
```
biodiv-index-phx
 │   README.md  
 │   biodiv-index-phx.ipynb      
 │
 └───data
      └───tl_2022_04_cousub
           |  tl_2022_04_cousub.cpg
           |  tl_2022_04_cousub.dbf
           |  tl_2022_04_cousub.prj
           |  tl_2022_04_cousub.shp
           |  tl_2022_04_cousub.shx
``` 
