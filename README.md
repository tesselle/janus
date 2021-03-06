
<!-- README.md is generated from README.Rmd. Please edit that file -->

# janus

<!-- badges: start -->

[![R-CMD-check](https://github.com/tesselle/janus/workflows/R-CMD-check/badge.svg)](https://github.com/tesselle/janus/actions)
[![codecov](https://codecov.io/gh/tesselle/janus/branch/master/graph/badge.svg)](https://codecov.io/gh/tesselle/janus)

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

## Deploy

``` r
## Set repositories
options(repos = c(tesselle = "https://tesselle.r-universe.dev",
                  CRAN = "https://cloud.r-project.org"))

## Assuming rsconnect is properly configured
deploy("seriate")
```

## Contributing

Please note that the **janus** project is released with a [Contributor
Code of Conduct](https://www.tesselle.org/conduct.html). By contributing
to this project, you agree to abide by its terms.
