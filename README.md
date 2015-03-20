dt
==

Command line R script for GNU make like functionality.

*If you it, please "star" it on Github.*

Installation Instructions
=========================

Put in in your `PATH` and make it executable to use.

This can be done in the following way:
1) Clone the repository.

2) Make a symlink of the dt-file into your bin-directory, e.g. (on Mac)
```splus
$ ln -s ~/path-to-the-dt-repository/dt /usr/local/bin/
```

3) Assure that you have installed all the dependencies
("methods", "optparse", "devtools", "roxygen2", "testthat", "covr")
The latter can be installed via 
```splus
devtools::install_github("jimhester/covr")
```