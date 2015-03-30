dt
==

Command line R script for GNU `make` like functionality.

**If you like dt, please "star" it on Github.**

Instructions
============

Installation
------------

Put in in your `PATH` and make it executable to use.

This can be done in the following way:

1) Clone the repository.


2) Make a symlink of the dt-file into your bin-directory, e.g.

`$ ln -s ~/path-to-the-dt-repository/dt /usr/local/bin/` (on Mac and Linux for all users)


`$ ln -s ~/path-to-the-dt-repository/dt ~/bin` (on Linux for your user only)


3) Assure that you have installed all the required R-packages:

```c("methods", "optparse", "devtools", "roxygen2", "testthat", "covr")```

The first five packages are available on CRAN, whereas the latter can be installed via 

```splus
devtools::install_github("jimhester/covr")
```

Usage
-----

Once `dt` is configured, you should be able to use it. Thus, just go into the root of a package's directory and try the different dt-commands, e.g. `$ dt check`, `$ dt install`, `$ dt test`, etc.


Contact
=======

Please use the issue tracker for problems, questions and comments. 
