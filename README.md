
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Santiago

<!-- badges: start -->
<!-- badges: end -->

The goal of Santiago is to contribute to psychological impacts on
travelers by examining the feelings of stress by users of active and
motorized modes of transportation.Furthermore, it also investigates the
importance that travelers attach to their feelings of stress. More
words.

## Installation

You can install the development version of Santiago from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("NiloofarNL/Santiago")
#> Downloading GitHub repo NiloofarNL/Santiago@HEAD
#>          checking for file 'C:\Users\bahman.notebook\AppData\Local\Temp\RtmpUleNSN\remotes4550602c6c\NiloofarNL-Santiago-abb62c8/DESCRIPTION' ...     checking for file 'C:\Users\bahman.notebook\AppData\Local\Temp\RtmpUleNSN\remotes4550602c6c\NiloofarNL-Santiago-abb62c8/DESCRIPTION' ...   v  checking for file 'C:\Users\bahman.notebook\AppData\Local\Temp\RtmpUleNSN\remotes4550602c6c\NiloofarNL-Santiago-abb62c8/DESCRIPTION' (652ms)
#>       -  preparing 'Santiago': (667ms)
#>    checking DESCRIPTION meta-information ...     checking DESCRIPTION meta-information ...   v  checking DESCRIPTION meta-information
#>       -  checking for LF line-endings in source and make files and shell scripts
#>       -  checking for empty or unneeded directories
#>       -  building 'Santiago_0.0.0.9000.tar.gz'
#>      
#> 
#> Installing package into 'C:/Users/bahman.notebook/Documents/R/win-library/4.1'
#> (as 'lib' is unspecified)
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(Santiago)
data("SantiagoSurvey")

## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/v1/examples>.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
