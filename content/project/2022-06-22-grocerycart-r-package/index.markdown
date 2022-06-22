---
title: grocerycart R Package
subtitle: "Scrape and clean grocery data from elGrocer and Ocado websites"
date: "2022-06-22"
slug: grocerycart-r-package
excerpt: "A bundle of functions to collect, clean & analyze data from 2 online grocery delivery services' website. Also includes 16 different ready to use grocery related datasets."
featured: no
alias:
  - /project/grocerycart-r-package/
categories:
  - rpackage
tags:
  - rpackage
links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/moamiristat/grocerycart
---



This package was built as a means to organize the scraping & cleaning functions that were created to **collect data from 2 online grocery services' websites** to be analyzed for the [grocery Shiny app dashboard](https://moamiristat.netlify.app/project/grocery/). Since then, it has evolved to include **16 different ready to use grocery related datasets** that include product details, store information and even randomly generated customers/orders/baskets database for a fake grocery store.

Thus, **the goal of the grocerycart package** is to provide:  

1. **A suite of collection functions** that scrape data from 2 online grocery services: [elGrocer](https://www.elgrocer.com) & [Ocado](https://www.ocado.com).  
2. **Cleaning functions** to prepare the scraped data for analysis.  
3. **Datasets containing details from real grocery stores** (e.g., products, prices, reviews).  
4. **Ready to use grocery data**: customer, order and basket datasets generated using real products. You can also generate your own grocery data.  

## Install Package

```r
# install from GitHub (make sure to set build_vignettes = TRUE to access vignette)
install.packages("devtools")

devtools::install_github("moamiristat/grocerycart", 
                         build_vignettes = TRUE)
```


## Usage
You may want to use this package for 1 of 2 reasons:  

1. Use the available grocery datasets to conduct your analysis (i.e., create graphs, analyze text review, conduct market basket analysis, build a dashboard, generate downloadable reports).   
2. Scrape and clean data from the 2 online grocery services' websites - [elGrocer](https://www.elgrocer.com) & [Ocado](https://www.ocado.com).  

## Getting Started & Vignette
Learn how you can scrape, clean and analyze grocery data with the functions in this package by running the following code in your R environment:  

```r
vignette("grocerycart")
```



## Data
You can view all 16 available datasets with the code below. Get more info about each dataset via `?*DatasetNAME*`.  

```r
data(package = "grocerycart")

# Get more info on a specific dataset
?oc_data
```


## Analysis
Here are examples of visualizations that can be created using the dataset in this package:  

<img src="https://raw.githubusercontent.com/moamiristat/grocerycart/main/most-reviewed-plot.jpg" height="350px" /> <img src="https://raw.githubusercontent.com/moamiristat/grocerycart/main/most-expensive-plot.jpg" height="350px" />

<img src="https://raw.githubusercontent.com/moamiristat/grocerycart/main/table.jpg" height="300px" />

<img src="https://raw.githubusercontent.com/moamiristat/grocerycart/main/cohort.jpg" height="350px" />

## Related Project
Learn how to use the `grocerycart` package by executing `vignette("grocerycart")`.  

Visit the [grocery Shiny app dashboard](https://moamiristat.netlify.app/project/grocery/) to access the grocery dashboard. 
