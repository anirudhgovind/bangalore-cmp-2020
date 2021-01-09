# Understanding the Comprehensive Mobility Plan for Bengaluru 2020

This repo contains all the files associated with 'Understanding the Comprehensive Mobility Plan for Bengaluru 2020' website. The website can be found at https://anirudhgovind.github.io/bangalore-cmp-2020/

Data was manually georeferenced by the authors/ contributors. While efforts have been taken to be as accurate and precise as possible, these locations may be imprecise or even inaccurate.

___

## Changelog

The table below provides information on the development of the project:

Version | Date | Description
-|-|-
0.1 | 20210107 | Website published with 100 geo-referenced proposals.
0.1 | 20210109 | Github repo made public after organization of files and folders. Raw data not made public yet.

## Data Sources

The table below describes data used in this project:

Type | Source | Description | Citation
-|-|-|-
Report | [Comprehensive Mobility Plan for Bengaluru 2020](http://www.urbantransport.kar.gov.in/docs/CMP%20Bengaluru%20-%20Final%20Report.pdf) | All proposals were sourced from this document and subsequently geo-referenced and analysed by the author and contributors | Bengaluru Metro Rail Corporation Limited (BMRCL), Directorate of Urban Land Transport (DULT), Infrastructure Development Corporation (Karnataka) Limited, 2020, Comprehensive Mobility Plan for Bengaluru 2020
Collaborative Mapping Site | [OpenStreetMap](www.openstreetmap.org) | Geodata to aid in analysis, representation and visualisation | Map data copyrighted OpenStreetMap contributors and available from https://www.openstreetmap.org"

## Software and Packages

R is the primary language used in all data management, geo-referencing and spatial analysis. A number of packages were used including the following:

Package | Purpose | Citation
-|-|-
distill | Website creation | JJ Allaire, Rich Iannone, Alison Presmanes Hill and Yihui Xie (2020). distill: 'R Markdown' Format for Scientific and Technical Writing. R package version 1.1. https://CRAN.R-project.org/package=distill
here | Accessing files | Kirill Müller (2020). here: A Simpler Way to Find Your Files. R package version 1.0.0. https://CRAN.R-project.org/package=here
mapboxapi | Walkability analysis and drawing isochrones | Kyle Walker (2020). mapboxapi: R Interface to 'Mapbox' Web Services. R package version 0.2. https://CRAN.R-project.org/package=mapboxapi
osmdata | Downloading data from OpenStreetMaps | Mark Padgham, Bob Rudis, Robin Lovelace, Maëlle Salmon (2017). osmdata Journal of Open Source Software, 2(14). URL https://doi.org/10.21105/joss.00305
sf | Dealing with spatial data and performing geometric operations | Pebesma, E., 2018. Simple Features for R: Standardized Support for Spatial Vector Data. The R Journal 10 (1), 439-446, https://doi.org/10.32614/RJ-2018-009
Tidyverse | Data wrangling | Wickham et al., (2019). Welcome to the tidyverse. Journal of Open Source Software, 4(43), 1686, https://doi.org/10.21105/joss.01686
tmap | Creation of static and interactive maps | Tennekes M (2018). “tmap: Thematic Maps in R.” _Journal of Statistical Software_, *84*(6), 1-39. doi:10.18637/jss.v084.i06 (URL: https://doi.org/10.18637/jss.v084.i06).