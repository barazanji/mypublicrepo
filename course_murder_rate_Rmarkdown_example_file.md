Report on Gun Murders
================
Rafael Irizarry
2022-02-03

## Introduction

This is a report on 2010 gun murder rates obtained from FBI reports. The
original data was obtained from [this Wikipedia
page](https://en.wikipedia.org/wiki/Murder_in_the_United_States_by_state).

We are going to use the following library:

``` r
library(tidyverse)
library(dslabs)
```

and load the data we already wrangled:

``` r
##load("rdas/murders.rda")
data(murders)
```

## Murder rate by state

We note the large state to state variability by generating a barplot
showing the murder rate by state:

![](course_murder_rate_Rmarkdown_example_file_files/figure-gfm/murder-rate-by-state-1.png)<!-- -->
