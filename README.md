
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mbquartR

<!-- badges: start -->

[![Codecov test
coverage](https://codecov.io/gh/alex-koiter/mbquartR/branch/main/graph/badge.svg)](https://app.codecov.io/gh/alex-koiter/mbquartR?branch=main)
[![R-CMD-check](https://github.com/alex-koiter/mbquartR/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/alex-koiter/mbquartR/actions/workflows/R-CMD-check.yaml)
[![pkgcheck](https://github.com/alex-koiter/mbquartR/workflows/pkgcheck/badge.svg)](https://github.com/alex-koiter/mbquartR/actions?query=workflow%3Apkgcheck)
<!-- badges: end -->

The goal of `mbquartR` is to provide an easy way to download the
Manitoba Original Survey Legal Descriptions data from
[DataMB](https://geoportal.gov.mb.ca/) and then to locate quarter
sections, and other land division types, in the province of Manitoba.
You can search by legal land description (e.g., NE-11-33-29W1) or by
lat/long coordinates (e.g., -101.4656, 51.81913). There is also a
convenient map function that plots the centres and outlines (polygons)
of the quarter sections on a map.

The Manitoba Original Survey Legal Descriptions data set covers the
entire province of Manitoba and there are over 900,000 parcels of land
that have a legal land description. `mbquartR` was created for those who
work with geospatial data in Manitoba, particularly those who are
working with rural or farm parcels of land where the legal land
description is commonly used as the method of identifying the location.
`mbquartR` also allows users to quickly go back and forth between
geographic coordinates and the legal land description. Most mapping
applications (e.g., Google Maps) can not find or route to a legal land
description, but you can with coordinates!

Checkout the [mbquartR website](http://alexkoiter.ca/mbquartR/) for
vignettes/code examples.

## What is a quarter section?

A quarter section in Manitoba is a land unit measuring 160 acres (~64.8
ha), representing a quarter of a square mile. It originates from the
[Dominion Land Survey
system](https://en.wikipedia.org/wiki/Dominion_Land_Survey), introduced
in the late 19th century to organize the European settlement and
colonization of Western Canada. The grid system covers most of the
province of Manitoba and organizes land into a hierarchy of quarter
sections, sections, townships, and ranges.

## Installation

You can install the development version of `mbquartR` like so:

``` r
# install.packages("devtools")
devtools::install_github("alex-koiter/mbquartR")
```

## This package is primarally maintained by:

**Alex Koiter** (koitera@brandonu.ca;
[@alex-koiter](https://github.com/alex-koiter)) Brandon University

Department of Geography & Environment

Brandon, Manitoba

Canada

## Access Constraints

The data is publicly available through the
[DataMB](https://geoportal.gov.mb.ca/), the province of Manitoba’s
public open data platform. The usage of this data is subject to the
[OpenMB Information and Data Use
License](https://www.gov.mb.ca/legal/copyright.html).

## Contributions

All suggestions are welcomed, big and small, on how to make this package
more robust, functional, and user friendly. Please read the
[contributing guide](https://alexkoiter.ca/mbquartR/CONTRIBUTING.html)
to learn more.

## Code of Conduct

Please note that this project is released with a [Contributor Code of
Conduct](https://ropensci.org/code-of-conduct/). By participating in
this package development you agree to abide by its terms.
