# immune-multiplex
This repository contains scripts and apps to show how salivary multiplex immune data changes with different processing/cleaning steps. It is a companion to the Riis, et al. book chapter.

The immunoassay and multiplex assay technology used to measure immune markers in saliva is very advanced. Commercially available tests consistently report detection limits in the very low pg/mL range and modern multiplexing assays have log-scale dynamic range. These advances in technology allow for the simultaneous testing of a large number of analytes. While this provides a wealth of information, highly correlated determinations of salivary immune markers from each individual may require advanced statistical modeling to parse the variance and individual effects of each immune marker alone and as part of a coordinated immune response. Investigators should also be particularly aware of issues related to collinearity among salivary immune markers. To explore these issues, we created R code to visualize differences in correlations between various salivary immune markers and their distributions when data have been cleaned or treated in different ways.

WHICH FILE SHOULD I USE?

-> Use the R Markdown file (.rmd) in R Studio if you wish to use your own data and run the analyses yourself. The first half of the script also includes code to synthesise your dataset in case you wish to share it without sharing the original data.

-> The PDF document (also available to download as HTML) is a version of the R Markdown code that has been run on simulated data (from a dataset of salivary immune markers collected from adolescents), with output (including correlation plots and graphs to visualize data distribution) underneath each code chunk. View this document if you are less familiar with R code. You will have to scroll past the synthesise code before you will start seeing correlation plots, etc.

-> Soon we will have a Shiny app available so readers can use a GUI to run different sections of the code in order to more easily and quickly visualize the differences in distributions and correlations when data has been cleaned and treated in different ways.

Suggestions and questions: michelle.byrne@gmail.com
