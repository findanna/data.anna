
<!-- README.md is generated from README.Rmd. Please edit that file -->

# data.anna

<!-- badges: start -->
<!-- badges: end -->

The goal of data.anna is to …

## Installation

You can install the development version of data.anna from
[GitHub](https://github.com/) with:

``` r
install.packages("devtools")
#> Installing package into '/usr/local/lib/R/site-library'
#> (as 'lib' is unspecified)
devtools::install_github("findanna/data.anna")
#> Downloading GitHub repo findanna/data.anna@HEAD
#> tidyselect (1.1.1 -> 1.1.2) [CRAN]
#> generics   (0.1.1 -> 0.1.2) [CRAN]
#> dplyr      (1.0.7 -> 1.0.9) [CRAN]
#> Installing 3 packages: tidyselect, generics, dplyr
#> Installing packages into '/usr/local/lib/R/site-library'
#> (as 'lib' is unspecified)
#> * checking for file ‘/tmp/RtmpF8vMUC/remotes23805d9113fc/findanna-data.anna-8b5b7e4/DESCRIPTION’ ... OK
#> * preparing ‘data.anna’:
#> * checking DESCRIPTION meta-information ... OK
#> * checking for LF line-endings in source and make files and shell scripts
#> * checking for empty or unneeded directories
#> * building ‘data.anna_0.0.0.9000.tar.gz’
#> Installing package into '/usr/local/lib/R/site-library'
#> (as 'lib' is unspecified)
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(data.anna)
extract_six_from_col(dataset = datasets::mtcars, column = "mpg")
#> [1] 33.9 32.4 30.4 30.4 27.3 26.0
extract_six_from_col(squirrels, "lat") 
#> [1] 40.79942 40.79925 40.79920 40.79898 40.79885 40.79876
```
