# The `rpart` package <img src="man/figures/rpart.png" alt="Rpart logo" style="float:right;height:232.25px" align="right" height="232.25">


[![CRAN_STATUS_BADGE](http://www.r-pkg.org/badges/version/rpart)](https://CRAN.R-project.org/package=rpart)
[![Downloads](http://cranlogs.r-pkg.org/badges/rpart)](https://CRAN.R-project.org/package=rpart)


## Project 3, part 1: jhu-statprogramming-fall-2023
### Building a website for an existing R package using `pkgdown`

Link to `pkgdown` website for `rpart`: https://jhu-statprogramming-fall-2023.github.io/biostat777-project3-part1-gringle1/
g

Customizations to `pkgdown` website: 

- changed theme
- changed code text color
- added a note with my name to the footer
- changed link color
- reordered side bar

`rpart` github: https://github.com/bethatkinson/rpart

## Original `rpart` readme below

This is the source code for the  `rpart` package, which is a recommended package in R.
It gets posted to the comprehensive R archive (CRAN) as needed after undergoing a thorough testing.


## Overview

The `rpart` code builds classification or regression models of a very
general structure using a two stage procedure; the resulting models can be
represented as binary trees. The package implements many of the ideas found
in the CART (Classification and Regression Trees) book and programs of
Breiman, Friedman, Olshen and Stone.  Because CART is the trademarked name
of a particular software implementation of these ideas and `tree` was used
for the Splus routines of Clark and Pregibon, a different acronym -
Recursive PARTitioning or rpart - was chosen.
