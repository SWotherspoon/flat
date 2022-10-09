# flat

<!-- badges: start -->
<!-- badges: end -->

This package provides smooths for mgcv that are constrained to be flat at on or both of the end knots.

## Installation

You can install the development version of flat like so:

``` r
remotes::install_github("SWotherspoon/flat")
```

## Usage

These smoothers are used with `gam` much like any other smoothers, but produce smooths that are flat 
(have derivative zero) at one or both end knots. As the knots control where the smoth is flat, the 
user should select the knots manually. The vignette provides examples of use.

