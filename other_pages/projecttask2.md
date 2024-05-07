---
title: Project Task 2
layout: default
parent: Final Project
nav_order: 2
---


<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>
<style type="text/css">
.indent {
 margin-left: 40px;
}
</style>

------------------------------------------------------------------------
# Final Project Task 2

For this project task, you will be required to “spatialize” your tabular census data and save the data 
to your “Data” subfolder in your final project folder. You will do this by joining your 
tabular data to your geographic data (from tigris)

------------------------------------------------------------------------

### Make Spatial

Open up **Lastname**_GEOG215_Project_DataPreparation.Rmd (created during Project Task #1). 
Add a new third-level heading called “Spatialize” below the work you completed for Project Task #1.
Insert an R code chunk where you make the non-spatial data into spatial data by executing a join. 
Remember, to execute a join, there must be a matching column between both the spatial dataset and the table. 
This column will be the “key” column. Once the data has been made “spatial,” you must map it using tmap 
(make sure that tmap is in interactive mode). You must create a choropleth using one of the 
variables that was initially “nonspatial.”

### Interpret

Additionally, you must provide a 4-6 sentence explanation (using narrative text in **Lastname**_GEOG215_Project_DataPreparation.Rmd ) that 
describes/explains the process of making your data spatial describes the spatial pattern you see in your map.

### Save

Save your joined data as a shapefile to your “Data” subfolder. (hint, use the `st_write()` command)

------------------------------------------------------------------------

### Deliverables

**Lastname**_GEOG215_Project_DataPreparation.Rmd
**Lastname**_GEOG215_Project_DataPreparation.html
