
<!-- README.md is generated from README.Rmd. Please edit that file -->

# healthdata

<!-- badges: start -->
<!-- badges: end -->

The `healthdata` package contains a set of health related datasets for
educational and experimental purposes.

## Installation

You can install the development version of healthdata like so:

``` r
#install.packages("devtools")
devtools::install_github("ielbadisy/healthdata")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(healthdata)
data(metacrc) # metastasis colorectal cancer
names(metacrc)
#>  [1] "id"              "age"             "sex"             "stage"          
#>  [5] "APC"             "type"            "location"        "carcinomatosis" 
#>  [9] "differentiation" "ECOG"            "fraction"        "LST"            
#> [13] "bone"            "metastasis"      "MSI"             "mutation"       
#> [17] "TMB"             "status"          "time"
```

## Developement

This package will be fed by datasets as they come in.
