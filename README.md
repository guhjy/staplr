
staplr <img src="logo.png" align="right" height="150" />
========================================================

<!-- README.md is generated from README.Rmd. Please edit that file -->
staplr
======

This package provides function to manipulate PDF files: merging multiple PDF files into one.

This package is still under development and this repository contains a development version of the R package *staplr*.

Installation
------------

#### Install pdftk

download and install [pdftk](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/) NB: this is not an R package!

#### Install staplr

You can install staplr from github with:

``` r
# install.packages("devtools")
devtools::install_github("pridiltal/staplr")
```

Example
-------

``` r
library(staplr)
staple_pdf()
```

References
----------

-   <https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/>