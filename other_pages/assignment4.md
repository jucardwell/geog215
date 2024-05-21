---
title: Assignment 4
layout: default
parent: Assignments
nav_order: 4
---




<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------
# Assignment 4
In this assignment you will script a function that defines the formatting for a tmap.
The data is from NCOneMap <https://www.nconemap.gov/datasets/ce5bbbe0c8194778859df0d3e02be3e7_0/explore>.
Remember that each line of code needs a descriptive comment. 

[**Download the Data Here**](https://drive.google.com/drive/folders/17P9jb3ur834jLVfQRBRj3laG6i75diUH?usp=sharing)
------------------------------------------------------------------------

### Create a new R Markdown document

1.  Save your .RMD file using the following naming convention:

-   **Lastname**\_GEOG215\_Assg**4**.Rmd
-   For example, Julia’s file would be: **Cardwell\_GEOG215\_Assg4.Rmd**

### Read in Data

1.  Add a code chunk at the top of your .Rmd. Load the tidyverse, sf,
    and tmap libraries.

2.  Add a **third-level heading** to your R Markdown file named, “Read
    in Data”. Below this heading, add a code chunk. In the chunk, use relative
    file paths to read in the fire station, emergency shelter, and hospital data


### Create Function

1. Add a **third-level heading** to your R Markdown file named, “Create Function”.
  Below this heading, add a code chunk.
   
3.  Create a function that takes two arguments, a spatial object, and a variable name.
   
4.  The function should develop a tmap based on the arguments that does the following:
  - Adds NC counties as the "basemap". **Hint: This means you will have two tm_shape + arguments
    and you will map the NC counties object first**
  - uses `tm_dots()` to map the "variable name" argument using the `Purples` color palette
    in the quantile style
  - moves the legend to the top of the map


### Create Maps

1. Add a **third-level heading** to your R Markdown file named, “Map”.
  Below this heading, add a code chunk.

2. Map fire stations, emergency shelters, and hospitals using the function created above. For
   fire stations, map the "staff" variable, for emergency shelters map the "capacity" variable, and
   for hospitals map the "hgenlic" variable (represents the number of available beds).

### Format your .Rmd File
1. Review the .Rmd help document. Format your .Rmd so that messages and warnings
   do not appear in the .knitted document. 

   
------------------------------------------------------------------------

### Deliverables

Upload your .Rmd and .html files to Canvas.
