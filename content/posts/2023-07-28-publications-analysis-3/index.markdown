---
title: Using R to analyze publications - part 3
subtitle: 
summary: An updated approach using bibliometrix the `bibilometrix` R package. 
author: Andreas Handel
draft: true
date: 2021-07-28T00:00:00
publishDate: 2021-07-28T00:00:00
lastmod: 2021-07-28T00:00:00
slug: publications-analysis-3
categories: 
- R
- Data Analysis
- bibliometrics
tags: ["R","Data Analysis","bibliometrics"]
featured: no
disable_jquery: no
image:
  caption: 'Photo by Rita Morais on Unsplash'
  focal_point: ''
  preview_only: yes
projects: []
---

# Overview

A bit more than a year ago, I needed some bibliometric information for my materials for 
wrote a 2-part blog post discus ([part 1](/posts/publications-analysis-1/) and )


# Required packages


```r
library(dplyr)
library(knitr)
library(bibliometrix)
```

# Loading data


```r
refs <- convert2df('handel_WOS_record.txt', dbsource = "wos", format = "plaintext")
```

```
## 
## Converting your wos collection into a bibliographic dataframe
## 
## 
## Warning:
## In your file, some mandatory metadata are missing. Bibliometrix functions may not work properly!
## 
## Please, take a look at the vignettes:
## - 'Data Importing and Converting' (https://www.bibliometrix.org/vignettes/Data-Importing-and-Converting.html)
## - 'A brief introduction to bibliometrix' (https://www.bibliometrix.org/vignettes/Introduction_to_bibliometrix.html)
## 
## 
## Missing fields:  CR 
## Done!
## 
## 
## Generating affiliation field tag AU_UN from C1:  Done!
```




