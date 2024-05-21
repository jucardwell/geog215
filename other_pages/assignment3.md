---
title: Assignment 3
layout: default
parent: Assignments
nav_order: 3
---




<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------
# Assignment 3
In this assignment you will "make data spatial", perform data 
cleaning steps and execute an Exploratory Data Analysis (EDA).
The data is from NCOneMap <https://www.nconemap.gov/datasets/ce5bbbe0c8194778859df0d3e02be3e7_0/explore>.
Remember that each line of code needs a descriptive comment. 

[**Download the Data Here**](https://drive.google.com/uc?export=download&id=1XuctmR6FtABZrT2UaCRgJ_9vTOVxsQnw)
------------------------------------------------------------------------

### Create a new R Markdown document

1.  Save your .RMD file using the following naming convention:

-   **Lastname**\_GEOG215\_Assg**3**.Rmd
-   For example, Julia’s file would be: **Cardwell\_GEOG215\_Assg3.Rmd**

### Read in Data

1.  Add a code chunk at the top of your .Rmd. Load the tidyverse, sf,
    and tmap libraries.

2.  Add a **third-level heading** to your R Markdown file named, “Read
    in Data”. Below this heading, add a code chunk. In the chunk, use a
    relative file path to read in the file "Colleges_and_Universities.csv"


### Clean Data

1. Add a **third-level heading** named "Clean Data". Create a chunk below
   
2.  Rename the "Enrollment at School" field to something without spaces.

3.  Make the data spatial. The latitude and longitude columns are in crs = 4326.

### Execute EDSA

1. Add a **third-level heading** named "Execute EDSA". Create a chunk below
   
2.  Create one descriptive statistics table for the enrollment column. 

3.  Create one non-map graphic for any of the descriptive columns. Make sure this graphic has a title
   and all other appropriate formatting. 

**Hint: You will probably get an error when trying to make the descriptive 
statistics table. You will need to figure out what Data Cleaning step you
still have to do**


### Map
1. Add a **third-level heading** named "Map". Create a chunk below

2. Create two interactive maps, one showing the enrollment column and one showing the degree column


### Format your .Rmd File
1. Review the .Rmd help document. Format your .Rmd so that messages and warnings
   do not appear in the knitted document. Also format your .Rmd so that the underlying code
   for the descriptive statistics table and the non-map graphic does not render in the .html.
   

------------------------------------------------------------------------

### Deliverables

Upload your .Rmd and .html files to Canvas.
