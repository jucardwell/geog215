---
title: Final Project Instructions
layout: default
parent: Final Project
nav_order: 4
---


<style>
div.blue { background-color:#ffdad2; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------

### Introduction

For your final project, you will be presenting the results from a
spatial data analysis in a reproducible format. This analysis will build on skills you have already executed in in-class activities and assignments, as well as the project tasks. 

Your spatial data analysis will explore a variable from the Census Bureau (I suggest using the American Community Survey) at a selected enumeration
unit (block group, tract, county, etc.) for a selected geographical area. You will execute Exploratory Spatial Data Analysis on the selected variable, and develop a research question around the variable that will likely require you to obtain additional data (either another variable from the Census Bureau or an additional spatial dataset). 

------------------------------------------------------------------------

### Required Components
-   Create spatial data from non-spatial data (e.g. join)
-   Produce descriptive statistics for your variable of interest
-   Produce at least one non-map graphic (for instance, a histogram or scatterplot)
-   Execute spatial clustering analysis (this should be Moran’s I and LISA)
-   Create at least two different interactive maps (this will likely be your LISA analysis and your variable of interest)
-   Develop one research question, with appropriate table(s),
    graphic(s), or statistical test results to analyze it

------------------------------------------------------------------------

### Reproducible

You must organize your analysis such that it is fully reproducible. The most important thing that needs to be done to ensure reproducibility is using relative file paths. 


------------------------------------------------------------------------


### Organization

This is a general breakdown of how your final project may be organized. 

#### *Introduction*

Should be a broad introduction to your topic and your research question. This should be approximately 3-4 paragraphs. You must include at least two outside data sources (at least one must be a peer-reviewed article). Your introduction should introduce the importance of your variable of interest and your geographical area, provide insight into current research on your geographical area/ variable of interest, introduce your research question and hypothesis and why you believe that hypothesis might be true (which will likely cite other literature)

#### *Data Preparation*

Describe data preparation and processing steps required to acquire and prepare your data for analysis. Please **do not** include the code you used to extract the data in your final project report .Rmd document!! This
should be in a separate .Rmd file (see Project Task \#1 and 2) that
should be submitted with your final project files.

#### *Data Description and Summary*
Include descriptive statistics, graph(s), and a plain text description of what you
learned about your data.

#### *Geographic Distribution and Spatial Clustering*
Includes map(s), results of clustering analysis, and a plain text
description of what you learned about your data.

#### *Research Question and Analysis*

Include your research question. Include a plain text description of
your method to answer the question. Include your answer to the research
question (your interpretation of the statistical test or graphic). You
may want to break this section up into subsections!

Note that your research analysis does not need to be entirely comprehensive (meaning you probably will not be able to fully answer your research question given the methods we have learned in this class). Instead, focus on developing a good spatially-oriented research question and applying an appropriate methodology from the ones that we have learned.

#### *Conclusion*

Include a summary of the entire project


------------------------------------------------------------------------

### Text Length

The narrative text portion (introduction, data description, research question, etc.) of your final project should be a minimum of 750 words. 


------------------------------------------------------------------------

### Formatting

There is a lot of flexibility regarding formatting your final project. Your final document must be readable and visually pleasing. For instance, you should use clear headers, you should not have code warnings and messages in the output, you may want to hide some of your code chunks in the output, you might want to look into R Markdown themes and the `kable` R package for tables. Your maps should be clear, your figures should have readable, well-described axis labels and titles, your tables should be well-formatted, etc. 

------------------------------------------------------------------------

### Deliverables

You should submit a zipped version of your final project folder. This zipped file should include
- Your "Code" folder with the .Rmd and .html of your data preparation (Project Task 1+2) document and your final project .Rmd and .html
- Your "Data" folder with your processed dataset (output of Project Task 2)

------------------------------------------------------------------------
