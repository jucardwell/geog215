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
In this assignment you will perform "make data spatial", perform data 
cleaning steps and execute an Exploratory Data Analysis (EDSA).
The data is from NCOneMap <https://www.nconemap.gov/datasets/ce5bbbe0c8194778859df0d3e02be3e7_0/explore>.
Remember that each line of code needs a descriptive comment. 

[**Download the Data Here**](https://drive.google.com/uc?export=download&id=1XuctmR6FtABZrT2UaCRgJ_9vTOVxsQnw)
------------------------------------------------------------------------

### Create a new R Markdown document

1.  If RStudio is open, close it and do not save your environment. Open
    RStudio and make sure that your environment is empty, then choose
    File | New File | R Markdown. *Note: to clear your Environment, find
    the button that looks like a broom in the Environment tab!*

    In the popup window, enter “Assignment \#3” for the title and for
    author, enter your name. Make sure that the type (on the left) is
    Document and the Default Output Format is HTML.

    Note that the new R Markdown document should have populated the
    “header” section to include the information you entered. For
    example, mine looks like this:

<style type="text/css">
.indent {
 margin-left: 40px;
}
</style>

    ---
    title: "Assignment #3"
    author: "Julia Cardwell"
    date: "5/29/2024"
    output: html_document
    ---

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

1.  Rename the "Enrollment at School" field to something without spaces.

2.  Make the data spatial. The latitude and longitude columns are in crs = 4326.

### Execute EDSA

1.  Create one descriptive statistics table for the enrollment column

2.  Create one non-map graphic for any of the descriptive columns.

**Hint: You will probably get an error when trying to make the descriptive 
statistics table. You will need to figure out what Data Cleaning step you
still have to do**


### Map
1.  Create two interactive maps, one showing the enrollment column and one showing the degree column  

------------------------------------------------------------------------

### Deliverables

Upload your .Rmd and .html files to Canvas.