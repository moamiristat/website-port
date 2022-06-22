---
title: "Learn to Apply STAT Concepts in R"
subtitle: "Interactive R tutorial covering the material taught in a typical graduate statistics course"
date: "2022-06-22"
slug: stat500r-tutorial
excerpt: "With the stat500r package you can run an interactive R tutorial - locally in your web browser - that teaches you how to use R by applying the concepts covered in a typical graduate statistics course."
featured: no
alias:
  - /collection/stat500r-tutorial/
categories:
  - rpackage
  - tutorial
tags:
  - rpackage
  - tutorial
links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/moamiristat/stat500r
---



With the **stat500r** package you can run an interactive R tutorial - locally in your web browser - that
teaches you how to use R by applying the concepts covered in a typical statistics course. In particular, the tutorial is meant to be accompanied by [Penn State’s STAT 500 course](https://online.stat.psu.edu/stat500/) (ps. this tutorial is not affiliated with Penn State University).

The **topics covered** include, but are not limited to:   
1. Visualizing quantitative and qualitative data using **ggplot2**.  
2. Constructing **t-tests, Chi-Square hypothesis tests, Simple Linear Regression and ANOVA models**.  
3. Calculating **confidence intervals**.  
4. Building **probability tree diagrams**.  
5. Exploring the **tidyverse**.  
6. And more…  

## Run Tutorial
**A live version of the tutorial can be run by typing the following commands in your R console** (it opens the tutorial locally on your computer as a new tab in your default web browser):  


```r
# needed to install the stat500r package (run only once)
install.packages("remotes")

# install stat500r package from github (run only once)
remotes::install_github("moamiristat/stat500r")

# run tutorial (run whenever you want to start up the tutorial)
learnr::run_tutorial("Introduction", "stat500r")
```


## Tutorial Screenshots
### Image 1: Tutorial is run locally
![](https://raw.githubusercontent.com/moamiristat/stat500r/main/inst/tutorials/Introduction/images/tutorial-1.png)

### Image 2: Interactive multiple choice questions
![](https://raw.githubusercontent.com/moamiristat/stat500r/main/inst/tutorials/Introduction/images/tutorial-2.png)

### Image 3: You can write & execute R code and view the output directly in the tutorial
![](https://raw.githubusercontent.com/moamiristat/stat500r/main/inst/tutorials/Introduction/images/tutorial-3.png)

### Image 4: Tips and tricks on how to customize your graphs
![](https://raw.githubusercontent.com/moamiristat/stat500r/main/inst/tutorials/Introduction/images/tutorial-4.png)

### Image 5: Learn about relevant R packages to help with analysis
![](https://raw.githubusercontent.com/moamiristat/stat500r/main/inst/tutorials/Introduction/images/tutorial-5.png)

### Image 6: Edit the code interactively in the tutorial
![](https://raw.githubusercontent.com/moamiristat/stat500r/main/inst/tutorials/Introduction/images/tutorial-6.png)

### Image 7: Edit and execute R code interactively
![](https://raw.githubusercontent.com/moamiristat/stat500r/main/inst/tutorials/Introduction/images/tutorial-7.png)

### Image 8: Become familiar with the tidyverse workflow
![](https://raw.githubusercontent.com/moamiristat/stat500r/main/inst/tutorials/Introduction/images/tutorial-8.png)

### Image 9: Reset all progress and code chunks
![](https://raw.githubusercontent.com/moamiristat/stat500r/main/inst/tutorials/Introduction/images/tutorial-9.png)

## Tutorial Screencasts
### Gif 1: How to run tutorial
<img src="https://user-images.githubusercontent.com/98935576/169015841-1484c19d-c7df-4cca-861e-9fdc2054aee1.mov" width="900" />

### Gif 2: How to edit code
<img src="https://user-images.githubusercontent.com/98935576/169015912-81c8d397-520b-4e5c-8fa5-0006a6aa76e5.mov" width="900" />

### Gif 3: How to reset code to default
<img src="https://user-images.githubusercontent.com/98935576/169015942-2ba75bd8-b1a8-4b32-bb96-4c09d6a9fb17.mov" width="900" />

## Packages Used

The tutorial was put together using the `learnr` package. All other packages contributed to the analysis portion of the tutorial.

- [learnr](https://rstudio.github.io/learnr/articles/learnr.html)  
- [tidyverse](https://tidyverse.tidyverse.org/index.html)  
- [grocerycart](https://github.com/moamiristat/grocerycart)  
- [DiagrammeR](https://github.com/rich-iannone/DiagrammeR)  
- [car](https://cran.rstudio.com/web/packages/car/index.html)  
- [correlation](https://www.rdocumentation.org/packages/correlation/versions/0.8.0)  
- [corrplot](https://cran.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html)  
- [crayon](https://github.com/r-lib/crayon)  
- [fontawesome](https://rstudio.github.io/fontawesome/index.html)  
- [GGally](https://ggobi.github.io/ggally/)  
- [ggbeeswarm](https://github.com/eclarke/ggbeeswarm)  
- [ggfortify](https://rpubs.com/sinhrks/plot_lm)  
- [ggmosaic](https://haleyjeppson.github.io/ggmosaic/)  
- [ggpubr](https://rpkgs.datanovia.com/ggpubr/)  
- [ggside](https://github.com/jtlandis/ggside)  
- [ggstatsplot](https://indrajeetpatil.github.io/ggstatsplot/)  
- [ggthemes](https://yutannihilation.github.io/allYourFigureAreBelongToUs/ggthemes/)  
- [ggVennDiagram](https://github.com/gaospecial/ggVennDiagram)  
- [Hmisc](https://hbiostat.org/R/Hmisc/  )
- [hrbrthemes](https://hrbrmstr.github.io/hrbrthemes/)  
- [remotes](https://remotes.r-lib.org)  
- [ridgeline](https://cran.r-project.org/web/packages/ggridges/vignettes/introduction.html)  
- [Rmisc](https://github.com/RyanHope/Rmisc)  
- [scales](https://scales.r-lib.org)  
- [viridis](https://cran.r-project.org/web/packages/viridis/index.html)
