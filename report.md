Report on Gun Murders
================
Rafael Irizarry
2018-12-09

Introduction
------------

This is a report on 2010 gun murder rates obtained from FBI reports. The original data was obtained from [this Wikipedia page](https://en.wikipedia.org/wiki/Murder_in_the_United_States_by_state).

We are going to use the following library:

``` r
library(tidyverse)
```

    ## Warning: package 'tidyverse' was built under R version 3.5.1

    ## Warning: package 'ggplot2' was built under R version 3.5.1

    ## Warning: package 'tibble' was built under R version 3.5.1

    ## Warning: package 'tidyr' was built under R version 3.5.1

    ## Warning: package 'readr' was built under R version 3.5.1

    ## Warning: package 'purrr' was built under R version 3.5.1

    ## Warning: package 'dplyr' was built under R version 3.5.1

    ## Warning: package 'stringr' was built under R version 3.5.1

    ## Warning: package 'forcats' was built under R version 3.5.1

and load the data we already wrangled:

``` r
load("rda/murders.rda")
```

Murder rate by state
--------------------

We note the large state to state variability by generating a barplot showing the murder rate by state:

    ## Warning: package 'bindrcpp' was built under R version 3.5.1

![](report_files/figure-markdown_github/murder-rate-by-state-1.png)
