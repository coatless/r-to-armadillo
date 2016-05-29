
[![Travis-CI Build Status](https://travis-ci.org/coatless/r-to-armadillo.svg?branch=master)](https://travis-ci.org/coatless/r-to-armadillo)

R To Armadillo (`r2armadillo`)
==============================

R is an amazing language to explore and communicate statistics with. However, when we care about attain results quickly, R's primary weakness is shown: speed. The objective of this repository is to strengthen this weakness by providing high performing R base functions within armadillo (and potentially eigen). Futhermore, as the code is written within C++, the code is able to be ported to different platforms at ease. Lastly, an additional benefit of this project is a repository containing programming examples by field.

Feel free to use the functions available within the repository.

Also, feel free to submit translations or new code of R functions via a pull request.

Project Details
===============

The functions written here act either as a means to replicate existing R functionality within armadillo or as a helpful interface to armadillo's code. These functions are meant to be easily included within existing code bases with minimal dependencies.

At some point in the future, these functions may end up being merged into the `RcppArmadillo` project.

Contributing
============

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.
