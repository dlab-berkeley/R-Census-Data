# D-Lab R Census Data Fundamentals Workshop

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](DATAHUB_LINK_HERE)
[![Binder](https://mybinder.org/badge_logo.svg)](BINDER_LINK_HERE)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for D-Lab R Census Data Fundamentals workshop. 

### Prerequisites
This workshop builds on fundamental concepts introduced in [R Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals).

The following courses are also helpful, but not required:
- [R Data Wrangling](https://github.com/dlab-berkeley/R-Data-Wrangling)
- [R Data Visualization](https://github.com/dlab-berkeley/R-Data-Visualization)
- [R Geospatial Fundamentals](https://github.com/dlab-berkeley/R-Geospatial-Fundamentals)

Check D-Lab's [Learning Pathways](https://dlab-berkeley.github.io/dlab-workshops/R_path.html) to figure out which of our workshops to take!

## Workshop Goals

In this workshop, we provide an overview of conducting U.S. Census data analysis and visualization in R. First, we’ll cover the basic concepts of U.S. Census Data. Then,
we’ll demonstrate how to call the census data API directly from R by using the R `tidycensus` package. 

Basic familiarity with R _is_ assumed. If you are not familiar with material in [R Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals), we recommend attending that workshop first.

## Learning Objectives

After this workshop, you will be able to:

- Understand different types of census data and the types of variables that are available.
- Understand the basic interface of the [data.census.gov](data.census.gov) website
- Use the `tidycensus` package to find census variables and download census data tables
- Produce graphs and maps of census data using ggplot and sf

This workshop does not cover the following:

- Principles of geospatial data analysis (map projections, spatial joins, etc.). These are covered in [R Geospatial Fundamentals](https://github.com/dlab-berkeley/R-Geospatial-Fundamentals).
- Advanced principles of data visualization. These are covered in [R Data Visualization](https://github.com/dlab-berkeley/R-Data-Visualization).


## Installation Instructions

We will use RStudio to go through the workshop materials, which requires installation of both the R language and the RStudio software. Complete the following steps:

1. [Download R](https://cloud.r-project.org/): Follow the links according to the operating system that you are running. Download the package, and install R onto your computer. You should install the most recent version (at least version 4.0).
2. [Download RStudio](https://rstudio.com/products/rstudio/download/#download): Install RStudio Desktop. This should be free. Do this after you have already installed R. The D-Lab strongly recommends an RStudio edition of 2022.02.0+443 "Prairie Trillium" or higher.
3. Download these workshop materials:
    * Click the green "Code" button in the top right of the repository information.
    * Click "Download Zip".
    * Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).
3. Optional: if you’re familiar with git, you can instead clone this repository by opening a terminal and entering [git clone git@github.com:dlab-berkeley/R-Census-Data.git].

## Is R not Working on Your Computer?

If you do not have R installed and the materials loaded on your
workshop by the time it starts, we *strongly* recommend using the UC Berkeley
Datahub to run the materials for these lessons. You can access the DataHub by
clicking the following button:

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](DATAHUB_LINK_HERE)

The DataHub downloads this repository, along with any necessary packages, and
allows you to run the materials in an RStudio instance on UC Berkeley's servers.
No installation is necessary from your end - you only need an internet browser
and a CalNet ID to log in. By using the DataHub, you can save your work and come
back to it at any time. When you want to return to your saved work, just go
straight to the [D-Lab DataHub](https://dlab.datahub.berkeley.edu), sign in, and
you click on the `[Workshop-Name]` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in the cloud, by clicking this button:

[![Binder](https://mybinder.org/badge_logo.svg)](BINDER_LINK_HERE)

By using this button, however, you cannot save your work.


## Run the Code

Now that you have all the required software and materials, you need to open the workshop notebook in RStudio:

1. Launch the RStudio software.
2. Use the file navigator to find the R-Census-Data folder you downloaded from Github.
3. Navigate to the `lessons` workshop folder and open the file `Census.Rmd` in RStudio.

# Additional Resources

Check out the following resources to learn more about Census data and mapping R:

* [Getting Started with the U.S. Census (UC Berkeley Library)](https://guides.lib.berkeley.edu/USCensus/Intro): Berkeley Library overview of census data
* [Basic usage of tidycensus](https://walker-data.com/tidycensus/articles/basic-usage.html): Summary of basic operations in `tidycensus`
* [Leaflet for R](https://rstudio.github.io/leaflet/): Introduction to interactive mapping with the `leaflet` package in R.
* [IPUMS Data and R](https://cran.r-project.org/web/packages/ipumsr/vignettes/ipums.html): Introduction to working with Census microdata in R using the `ipumsr` package


# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab [Language] Workshops

Here are other R workshops offered by the D-Lab:

## Basic Competency

* [R Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals)
* [R Data Wrangling](https://github.com/dlab-berkeley/R-Data-Wrangling)
* [R Data Visualization](https://github.com/dlab-berkeley/R-Data-Visualization)

## Intermediate/Advanced Competency

* [R Geospatial Fundamentals](https://github.com/dlab-berkeley/R-Geospatial-Fundamentals)
* [R Machine Learning](https://github.com/dlab-berkeley/R-Machine-Learning)
* [R Deep Learning](https://github.com/dlab-berkeley/R-Deep-Learning)

# Contributors

[Alex Ramiller](https://dlab.berkeley.edu/people/alex-ramiller)
