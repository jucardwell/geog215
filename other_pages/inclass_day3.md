---
title: 
layout: default
nav_exclude: true
---

******

### Execute commands in R from an R script 
1. Create a folder in your "exercises" folder called **in_class_05172024**. 
   
2. Download [GEOG215-ex3-RCommands.R](https://drive.google.com/uc?export=download&id=1Pev98uA_jKvQNn61euxVcQzEiQeG1MF7) into **in_class_05172024**

3. Open the document in R studio. Read through the document, execute the commands, and answer the questions in the script.  

******

### Create an R Markdown document

You will now create a simplified R Markdown document with some of the commands that you have run in the Rcommands file. 

4. In RStudio, select File -> New File -> R Markdown

5. Once you have the file open, select File -> Save As, and save the file using the following naming convention:

    **Lastname**_GEOG215_InClass1.Rmd in your **in_class_05172024**
    For example, Julia's file would be: **Cardwell**_GEOG215_InClass1.Rmd

7. Change the title of the document to **GEOG 215, In Class #1** and change the name to **your name**. When, complete, knit to HTML to make sure everything worked. 

8. Remember that the easiest way to make sure that your working directory is set is to make sure a file is saved into the correct location and then re-open it from that location. Do this now. 

9. Create a third-level heading called "Load Libraries". To make a third level heading, type "### "And write your header. Add a code chunk below and load the tidyverse library. You can create a code chunk by clicking the green "c" box at the top of the document. 

7. Create another third-level heading called "Read in and Modify Data". Add a code chunk below. Return to the "GEOG215-ex3-RCommands.R" and identify the command that reads in the nc.mar object. Copy this command to the code chunk. Then, identify the command that modifies the nc.mar object to create a new column representing average marriages. Copy this command to the code chunk. Add descriptive comments for both of these commands. 

8. Create another third-level heading called "Plotting Data". Add a code chunk below and modify this code chunk to only print the output, not the code. Return to the "GEOG215-ex3-RCommands.R" and identify the command that makes a plot (it can be either of the plots). Copy this command to the code chunk. Add a descriptive comment for this command.

9. Create another third-level heading called "Practicing In Line Code". Use inline code to add the number of rows in the nc.mar object. 

******

### Deliverables
Upload your .R, .Rmd and .html files to Canvas.
