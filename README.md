# RANN 
[![Release Version](https://img.shields.io/github/release/jefferislab/RANN.svg)](https://github.com/jefferislab/RANN/releases/latest) 
[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/RANN)](https://CRAN.R-project.org/package=RANN) 
[![R-CMD-check](https://github.com/jefferis/RANN/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/jefferislab/RANN/actions/workflows/R-CMD-check.yaml)
[![Codecov test coverage](https://codecov.io/gh/jefferislab/RANN/graph/badge.svg)](https://app.codecov.io/gh/jefferislab/RANN)
[![Downloads](https://cranlogs.r-pkg.org/badges/RANN?color=brightgreen)](https://www.r-pkg.org/pkg/RANN)

Finds the k nearest neighbours for every point in a given dataset
in O(N log N) time using Arya and Mount's ANN library (v1.1.3). There is
support for approximate as well as exact searches, fixed radius searches
and bd as well as kd trees.

This package implements nearest neighbors for the Euclidean (L2) metric.
For the Manhattan (L1) metric, install the [RANN1](https://github.com/jefferislab/RANN/tree/master-L1) package.

For further details on the underlying ANN library, see https://www.cs.umd.edu/~mount/ANN.

## Installation
### Released versions
The recommendation is to install the released version from [CRAN](https://cran.r-project.org/) by doing:

```r
install.packages("RANN")
```

### Bleeding Edge
You can, however, use the **remotes** package to install the development version:

```r
# install.packages("remotes")
remotes::install_github("jefferis/RANN")
```

## Feedback
Please feel free to:

* submit suggestions and bug-reports at: <https://github.com/jefferislab/RANN/issues>
* send pull requests after forking: <https://github.com/jefferislab/RANN/>
* e-mail the maintainer: <jefferis@gmail.com>

## Copyright and License
see [inst/COPYRIGHT](inst/COPYRIGHT) and [DESCRIPTION](DESCRIPTION) files for copyright and license information.
