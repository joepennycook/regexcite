
<!-- README.md is generated from README.Rmd. Please edit that file -->

# regexcite

<!-- badges: start -->
<!-- badges: end -->

The goal of regexcite is to help me learn how to set up packages,
following the examples in *R Packages* by Hadley Wickham and Jennifer
Bryan.

## Installation

You can install the development version of regexcite from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("joepennycook/regexcite")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(regexcite)

x <- ("up-down-left-right")
str_split_one(x, pattern = "-")
#> [1] "up"    "down"  "left"  "right"
```
