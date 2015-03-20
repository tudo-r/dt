dt
==

Command line R script for GNU `make` like functionality.

*If you it, please "star" it on Github.*

Installation Instructions
=========================

Put in in your `PATH` and make it executable to use.

This can be done in the following way:

1) Clone the repository.


2) Make a symlink of the dt-file into your bin-directory, e.g.

`$ ln -s ~/path-to-the-dt-repository/dt /usr/local/bin/` (on Mac)


3) Assure that you have installed all the required R-packages:

```c("methods", "optparse", "devtools", "roxygen2", "testthat", "covr")```

The first five packages are available on CRAN, whereas the latter can be installed via 

```splus
devtools::install_github("jimhester/covr")
```
