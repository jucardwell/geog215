---
title: Assignment 2
layout: default
parent: Assignments
nav_order: 2
---




<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------
# Assignment 2
In this assignment, you will read in three spatial datasets and use the
tmap package to create static and interactive maps. The bus data is from
<https://opendata-townofchapelhill.hub.arcgis.com/> and the Carrboro
tree data is from <https://www.townofcarrboro.org/145/Download-Data>.
Make sure each line of code has a descriptive comment. 

[**Download the Data Here**](https://drive.google.com/drive/folders/18kvs_32wH9CPwR9fHaecMSSAttGxCGZo?usp=sharing)
------------------------------------------------------------------------

### Create a new R Markdown document

1.  Download the data into the Assignment 2 folder. Save a new .RMD file in your Assignment 2 folder using the following naming convention:

-   **Lastname**\_GEOG215\_Assg**2**.Rmd
-   For example, Julia’s file would be: **Cardwell\_GEOG215\_Assg2.Rmd**

### Read in Data

1.  Add a code chunk at the top of your .Rmd. Load the tidyverse, sf,
    and tmap libraries.

2.  Add a **third-level heading** to your R Markdown file named, “Read
    in Data”. Below this heading, add a code chunk. In the chunk, use a
    relative file path to read in (using the `st_read()` command) the
    file named “Chapel\_Hill\_Transit\_Bus\_Stops.shp” and assign it to
    an object called `bus_stops`, the file named
    “Weekday\_Bus\_Routes\_2022.shp” and assign it to an object called
    `bus_routes`, and the file named “TreeCover2017.shp” and assign it
    to an object called `carrboro_trees`.

3.  Using the console, check the coordinate reference systems of all the
    layers using the `st_crs()` command. If all of the layers are not in
    the same reference system, use the `st_transform()` command to put
    them all in the same reference system.

### Map Bus Stops and Bus Routes

1.  Under the code chunk that reads in data, insert a **third-level
    heading** to your R Markdown file named, “Map Bus Stops and Bus
    Routes”. Create a static map that shows bus stops as a single color
    and shows bus routes categorized by the “Name” column. Make sure the tmap has
    a title. You will note that sometimes, tmap creates a legend that overlaps
    the map area. Add this code to your tmap command `+ tm_layout(legend.outside = TRUE) `

### Map Tree Species in Carrboro

1.  Under the code chunk that maps bus stops and bus routes, insert a
    **third-level heading** named “Map Tree Species in Carrboro”. Add an
    **interactive** map (with a basemap) that displays trees in Carrboro
    and classifies the trees by the “COMP\_” column (which represents
    the type of trees). You should get an error. Sometimes data from the web
    contains geometry errors which prevent tmap from mapping them. Add this command
    `%>%st_make_valid()` to your tree read in command to fix any invalid geometries. 

3. Write a command to make and print a summary table that sums the amount of acres
   of any tree type in Carrboro. Hint: you will use the `summarise` command. 

### Format your .Rmd File
1. Review the .Rmd help document. Format your .Rmd so that messages and warnings
   do not appear in the .knitted document.
   
------------------------------------------------------------------------

### Deliverables

Upload your .Rmd and .html files to Canvas.
