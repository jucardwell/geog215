---
title: Assignments
layout: default
nav_enabled: true
nav_order: 5
has_children: true
---

<style>
div.blue { background-color:#ffdad2; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------

### Introduction

For your final project, you will be presenting the results from an
spatial data analysis in a reproducible format. You will create a report
that will detail all the steps required to extract your data, prepare it
for analysis, and conduct a basic ESDA and clustering analysis, as well
as a description and interpretation of the data and its spatial pattern.

------------------------------------------------------------------------

### Required Components

Below is a list of required components for your final project report.
These are purposefully broad to cover the large range of projects and
data in our class. You already have code to accomplish each of these (in
assignments, exercises, and resources); you simply need to modify it and
clean it up.

-   Inline R code  
-   Create spatial data from non-spatial data (e.g. join)
-   Some descriptive statistics for your variable of interest, including
    important information about the number of observations, central
    tendency, and variation  
-   One non-map graphic for your variable of interest (e.g., histogram,
    boxplot, bar chart)  
-   One map layout with two maps displayed in sync  
-   Spatial clustering analysis (this should be Moran’s I and LISA)  
-   One table presented using kable (can be some of your data or can use
    to present descriptive statistics)
-   BONUS POINTS FOR: One research question, with appropriate table(s),
    graphic(s), or statistical test results to answer it

------------------------------------------------------------------------

### Reproducible

You must organize your analysis such that it is fully reproducible. So,
you will be required to upload a .zip file containing your code and your
data. Julia will attempt to “re”-knit your .Rmd file on his computer
(**you must also include the .Rmd file that you used to extract and join
your data!**).

What does this mean? It means that you will have to **1) be extremely
organized and 2) use relative file paths in your code**.

#### Testing Reproducibility

**Did you know that you can test whether your code is reproducible by
yourself? (this is assuming you used ALL relative file paths)**. To
test, 1) make a copy of your entire final project folder, 2) paste it in
a completely different location on your computer, 3) close RStudio, and
then open your .Rmd file, 4) try to knit the document. You can also send
your .zip and have them attempt to knit your code!

------------------------------------------------------------------------

### Other Requirements

-   All commands in your R Code Chunks must have short, descriptive
    comments  
-   All maps (tmap) must be interactive
-   All graphics must have understandable axis labels  
-   Must change the default background map for tmap

------------------------------------------------------------------------

### Organization

You should use the following headers (or something very similar) for
your report. I have also included rough guides for the **narrative
text** and **graphical** material to be included in each. Your code
should be broken up into chunks that correspond to each section (and is
located in that section in the document). The narrative text in the
preparation and analysis sections should summarize (in plain text) what
is occurring in your R code, and include any interpretation of the
output as appropriate.

## *Introduction*

*Should be a broad introduction to your topic. Should be one paragraph
(roughly 4-6 sentences)*

## *Data Preparation*

*Include a brief, plain text explanation of your data sources and an
overview of the processing required to acquire and prepare your data for
analysis. Make sure to include any data preparation steps you performed
prior to reading the data into R. Do NOT print the output of a `print()`
or `str()` of your data in your code.*

**IMPORTANT NOTE:** Please DO NOT include the code you used to
**extract** the data in your final project report .Rmd document!! This
should be in a separate .Rmd file (see Project Task \#1 and 2) that
should be submitted with your final project files.

**IMPORTANT NOTE 2:** Only read in data that you are using in the
analysis!

## *Exploratory Spatial Data Analysis*

#### *Data Description and Summary*

*Include descriptive statistics (e.g., number of observations, central
tendency, variation), graph(s), and a plain text description of what you
learned about your data.*

#### *Geographic Distribution and Spatial Clustering*

*Includes map(s), results of clustering analysis, and a plain text
description of what you learned about your data.*

#### *Research Question and Analysis (for bonus points)*

*Include your research question. Include a plain text description of
your method to answer the question. Include your answer to the research
question (your interpretation of the statistical test or graphic). You
may want to break this section up into subsections!*

## *Conclusion*

*Include a very brief summary of the entire project (e.g., 2-3
sentences).*

### *Document Statistics*

*Include a kable table showing word count (use plugin)*

------------------------------------------------------------------------

### Text Length

The narrative text portion of your final project should be a minimum of
500 words and maximum of 750 words. This is roughly equivalent to 2-3
double-spaced typed pages.

------------------------------------------------------------------------

### Formatting

Your report should have a **floating Table of Contents**. Your report
should also have **code folding** enabled. Add the following options to
**every** R code chunk: `message = FALSE, warning = FALSE`. Use
**horizontal lines** to delineate sections of your report. These have
been integrated in some of the .Rmd code used in class exercises, exams,
and resource documents. Make sure that formatting in the knitted .html
output is correct (e.g., headers show up as headers, inline R code works
correctly, spacing is correct); this has been an issue in past
assignments.

------------------------------------------------------------------------

### Suggested Approach

I suggest that you create a new, blank .Rmd document for your final
report. Then use copy/paste to insert the **relevant code chunks** from
your prior assignments. I **do not** suggest working “backward” from
your current working .Rmd files (e.g., cutting out pieces you do not
want)… as your final project document will need to be organized in a
somewhat different manner and serves a different purpose.

------------------------------------------------------------------------

### Evaluation

Your project submission will be evaluated on five aspects,

1.  Organization and clarity of the code and data  
2.  Organization and clarity of the R Markdown report  
3.  Quality of the narrative text and interpretation of the data  
4.  Quality of the graphs, maps, tables and other material in the R
    Markdown report  
5.  Quality and robustness of the interpretation of the data and
    analysis results

**IMPORTANT NOTE:** the importance of creating a clean and organized
final report document cannot be overemphasized! Please take a moment to
review the final knitted document to make sure that everything has
rendered correctly, the formatting is correct, and it looks “nice” and
easy to read.

**IMPORTANT NOTE 2:** you will be penalized if you include data and/or
code in your report that is not accomplishing anything (e.g., you have
blindly copy/pasted from your prior assignments without considering what
the code is accomplishing or why it is there). Please take a moment to
review the final document to make sure that you are only including
code/analysis that is required (above).

**IMPORTANT NOTE 3:** please reread the prior notes again, take a look
at your final knitted document, and ask yourself, “does this look like a
clean, clear, and organized report that will makes it easy for Julia to
find all the required elements and to understand my analysis?”

------------------------------------------------------------------------

### Deliverables

Make sure that your .Rmd file knits. When you are finished, zip up your
files/folders (this is extremely easy to do on Mac and Windows
computers). Upload a .zip file that contains all the files required to
perform your analysis on Canvas

------------------------------------------------------------------------
