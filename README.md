# ⚠️ THIS PROJECT IS ARCHIVED ⚠️

Keeping this as a potential R package to host R functions of potential common usage seems redundant, since there is also the [library-code](https://github.com/ocbe-uio/library-code) repository that does the same thing, but is language-agnostic. If you have any code that you'd like to share with your colleagues because it could be useful in multiple projects, please share it there. This repository might be deleted in the future, unless there's specific demand for an R package that does this.

# Introduction to the `ocbe` software

`ocbe` is an R package containing miscellaneous functions of potential common interest to all OCBE researchers as well as the scientific community in general.

# Goal

The goal of this package is to make it easier for OCBE staff members to share R code that is too small to become its own package but too potentially useful to gather dust in one person's computer.

After an initial stage of gathering functions, our objective is to publish this package on CRAN, the official R package repository.

# Usage

The development version of `ocbe` can be installed by running the following in an R terminal.

```r
remotes::install_github("ocbe-uio/ocbe")
```

After installing the package, you can load it with `library("ocbe")`. For a list of currently-implemented functions, run `help("ocbe")` afterwards.
