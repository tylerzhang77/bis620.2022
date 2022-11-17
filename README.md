
<!-- README.md is generated from README.Rmd. Please edit that file -->

# bis620.2022

<!-- badges: start -->

[![R-CMD-check](https://github.com/tylerzhang77/bis620.2022/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/tylerzhang77/bis620.2022/actions/workflows/R-CMD-check.yaml)
[![test-coverage-check](https://github.com/tylerzhang77/bis620.2022/actions/workflows/test-coverage.yaml/badge.svg)](https://github.com/tylerzhang77/bis620.2022/actions/workflows/test-coverage.yaml)
[![lint](https://github.com/tylerzhang77/bis620.2022/actions/workflows/lint.yaml/badge.svg)](https://github.com/tylerzhang77/bis620.2022/actions/workflows/lint.yaml)
<!-- badges: end -->

The goal of this package is to plot accelerometry data.

## Installation

You can install the development version of bis620.2022 from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("tylerzhang77/bis620.2022")
```

## Example

This is a basic example which shows you how to make a plot with
accelerometry data:

``` r
data("ukb_accel")
accel_plot(ukb_accel[1:100, ])
```
