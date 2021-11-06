
<!-- README.md is generated from README.Rmd. Please edit that file -->

# janus

<!-- badges: start -->

[![R-CMD-check](https://github.com/tesselle/janus/workflows/R-CMD-check/badge.svg)](https://github.com/tesselle/janus/actions)

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
<!-- badges: end -->

## Overview

A collection of [**shiny**](https://shiny.rstudio.com) application that
provides exhanced graphical user interfaces for the
[tesselle](https://www.tesselle.org) packages.

## Installation

You can install the latest version of **janus** from [our
repository](https://tesselle.r-universe.dev) with:

``` r
install.packages("janus", repos = "https://tesselle.r-universe.dev")
```

## Usage

``` r
## Load the package
library(janus)

## Run the app for matrix seriation
run_app("seriate")
```

## Deploy on shinyapps.io

Download the [package
source](http://github.com/tesselle/janus/archive/master.zip) from
GitHub, open the `janus.Rproj` in RStudio, then deploy to
[shinyapps.io](https://www.shinyapps.io) (assuming
[**rsconnect**](https://github.com/rstudio/rsconnect) is properly
configured).

``` r
## Load package
devtools::load_all(".")

## Deploy
deploy("seriate")
```

## Contributing

Please note that the **janus** project is released with a [Contributor
Code of Conduct](https://www.tesselle.org/conduct.html). By contributing
to this project, you agree to abide by its terms.
