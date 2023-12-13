# biodiv-index-phx
This Github repository contains a Python (.ipynb) notebook conducting an analysis of change in Biodiversity Intactness Index from 2017 to 2020 in the Phoenix area. We use two datasets to conduct this analysis. BII data is part of the MPC STAC catalog, and Phoenix shapefiles were sourced from Census County Subdivision shapefiles for Arizona. 


## Title: Analysis of Change in Biodiversity Intactness Index from 2017 to 2020 in the Phoenix area
#### 🤠 Author: Flora Hamilton | floraham@github.io 


#### 📦 Repo Link: https://github.com/floraham/biodiv-index-phx


#### 🔎 Dataset descriptions:

##### BII data
- This dataset is part of the MPC STAC catalog. We access the ‘iobiodiversity’ collection and look for the 2017 and 2020 rasters covering Phoenix subdivision. The following coordinates for a bounding box define our search: [-112.826843, 32.974108, -111.184387, 33.863574]

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
