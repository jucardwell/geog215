---
title: Assignment 5
layout: default
parent: Assignments
nav_order: 5
---




<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------
# Assignment 5
In this assignment you execute a analysis to determine what hospital is closest to each of the
nursing homes in North Carolina. The data is from NCOneMap (https://www.nconemap.gov/)

[**Download the Data Here**](https://drive.google.com/drive/folders/1s-gXlmbywxuYR1XUw8f8RnMZJdkb698O?usp=sharing)
------------------------------------------------------------------------

### Create a new R Markdown document

1.  Save your .RMD file using the following naming convention:

-   **Lastname**\_GEOG215\_Assg**5**.Rmd
-   For example, Julia’s file would be: **Cardwell\_GEOG215\_Assg5.Rmd**

### Read in Data

1.  Add a code chunk at the top of your .Rmd. Load the tidyverse, sf,
    and tmap libraries.

2.  Add a **third-level heading** to your R Markdown file named, “Read
    in Data”. Below this heading, add a code chunk. In the chunk, use relative
    file paths to read the hospital and nursing home data 


### Execute Spatial Analysis 

1. Add a **third-level heading** to your R Markdown file named, “Execute Spatial Analysis”.
   In a new code chunk, write a command that identifies the hospital that is closest to each
   nursing home in the state. In the hospital dataset, the objectid field is equal to the index.


### Data Processing and Mapping

1. Add a **third-level heading** to your R Markdown file named, “Data Processing and Mapping”.
  Below this heading, add a code chunk.

2. Create an interactive map of nursing homes across the state where the nursing homes are color
   coded by the closest hospital. 
   
3. Create a summary table for hospitals which calculates the number of nursing homes that each hospital
   is closest for.

### Format your .Rmd File
1. Review the .Rmd help document. Format your .Rmd so that messages and warnings
   do not appear in the knitted document.
   
   
------------------------------------------------------------------------

### Deliverables

Upload your .Rmd and .html files to Canvas.
