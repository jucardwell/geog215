---
title: Assignment 2
layout: default
nav_exclude: true
parent: Assignments
nav_order: 2
---




<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------

In this assignment, you will read in three spatial datasets and use the
tmap package to create static and interactive maps. The bus data is from
<https://opendata-townofchapelhill.hub.arcgis.com/> and the Carrboro
tree data is from <https://www.townofcarrboro.org/145/Download-Data>

[**Download the Data Here**](https://drive.google.com/drive/folders/1eviZk_uSUp8A53Eer5tolhVZIs2EnbGK?usp=sharing)
------------------------------------------------------------------------

### Create a new R Markdown document

1.  If RStudio is open, close it and do not save your environment. Open
    RStudio and make sure that your environment is empty, then choose
    File | New File | R Markdown. *Note: to clear your Environment, find
    the button that looks like a broom in the Environment tab!*

    In the popup window, enter “Assignment \#2” for the title and for
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
    title: "Assignment #2"
    author: "Julia Cardwell"
    date: "5/29/2024"
    output: html_document
    ---

1.  Save your .RMD file using the following naming convention:

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
    `bus_routes`, and the file named “ParksNSchools.shp” and assign it
    to an object called `carrboro_parks`.

3.  Using the console, check the coordinate reference systems of all the
    layers using the `st_crs()` command. If all of the layers are not in
    the same reference system, use the `st_transform()` command to put
    them all in the same reference system.

### Map Bus Stops and Bus Routes

1.  Under the code chunk that reads in data, insert a **third-level
    heading** to your R Markdown file named, “Map Bus Stops and Bus
    Routes”. Create a static map that shows bus stops as a single color
    and shows bus routes categorized by the “Name” column.

So far, we have only mapped polygons. In this case the `bus_stops` data
is points and the `bus_routes` data is lines. Review the tmap
documentation on Canvas to determine how to add lines and points to a
tmap.

### Map Tree Species in Carrboro

1.  Under the code chunk that maps bus stops and bus routes, insert a
    **third-level heading** named “Map Tree Species in Carrboro”. Add an
    **interactive** map (with a basemap) that displays trees in Carrboro
    and classifies the trees by the “COMP\_” column (which represents
    the type of trees)

2.  Spell check your .Rmd document (Edit | Check Spelling or the little
    button in RStudio with an “ABC” and check mark). Knit your document.
    **Review the knitted .html version of your assignment and look for
    issues/problems with formatting!** I suggest viewing the output in
    an actual browser rather than in RStudio’s browser (look for the
    Open in Browser button of the popup window with the knitted output).

------------------------------------------------------------------------

### Deliverables

Upload your .Rmd and .html files to Canvas.
