---
title: "Report On Gun Murders"
author: "Course Data Science"
date: "2023-06-14"
output: html_document
---



## Introduction

This is a report on 2010 gun murder rates obtained from FBI reports. The original data was obtained from [this Wikipedia page](https://en.wikipedia.org/wiki/Murder_in_the_United_States_by_state).

We are going to use the following library:


```r
library(tidyverse)
```
  
and load the data we already wrangled:


```r
load("rda/murders.rda")
```

## Murder rate by state 

We note the large state to state variability by generating a barplot showing the murder rate by state:

<img src="report_files/figure-html/murder-rate-by-state-1.png" width="672" />
