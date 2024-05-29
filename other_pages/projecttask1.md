---
title: Project Task 1
layout: default
parent: Final Project
nav_order: 1
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
# Final Project Task 1

For this assignment you are required to demonstrate (within an R
Markdown document) that you can extract census data using the tigris and
tidycensus packages,and display/manipulate each data layer.

------------------------------------------------------------------------
# [**Download the Help Document Here**](https://drive.google.com/uc?export=download&id=1jGwN_okjDHMhwz8pBGd8IGC_iYwhZ4v4)
### Set Up

On your computer, set up a folder structure for your final project if
you have not done so. I would suggest having a top-level folder called
“Final\_project” that is located within the folder you’re storing the
information for Geography 215. Within that folder, you should have a
“Data” and a “Code” subfolder. Take a screenshot of your folder
structure and submit it with the assignment.

### Extract and Work with Data

As discussed in class, the data for the final project must come from the
Census Bureau. You will be using the tidycensus and tigris packages to
extract a tabular and spatial dataset. Follow instructions in
Extracting-FinalProject-Data.Rmd.

Create a new .Rmd document and save it as
**Lastname**\_GEOG215\_Project\_DataPreparation.Rmd (using your last
name) and save it (I would suggest saving it to a location such as
**Final\_project/Code** &lt;&lt; hint hint).

**Detailed requirements for the .Rmd document:**

-   Include a separate R code chunk (with a third level heading) that
    loads libraries

-   Include a separate R code chunk (with a third level heading) that
    extracts data from the American Community Survey and a spatial
    dataset to match your social data. Follow instructions in
    Extracting-FinalProject-Data.Rmd. Within that same code chunk, make
    **one** minor calculation or modification of one of the layers, such
    as “sum a column”, “subset/filter the observations”, or “change the
    name of a column”. For most people, they will create a percent or
    ratio from an estimate and total (shown in the
    Extracting-FinalProject-Data.Rmd). If you do not need to create a
    percent, you may chose to filter out geographies with NULL values,
    or change a column name.

-   Using regular text below the previous code chunk, explain the minor
    calculation or modification of the layer that you performed in the
    code chunk above. How do you know the command worked? (2-3
    sentences)

-   Include a separate R code chunk (with third level heading) that makes a simple map using the spatial data layer. 


**Other requirements:**

-   Use headings in the .Rmd document to separate R code chunks  
-   Make sure to comment your R commands
-   Spellcheck and then knit your document when complete  
-   Review the knitted output to make sure that everything worked
    correctly!

------------------------------------------------------------------------

### Deliverables

*Lastname*\_GEOG215\_Project\_DataPreparation.Rmd  
*Lastname*\_GEOG215\_Project\_DataPreparation.html  
*Lastname*\_project\_folders.xxx

 
