dt
==

Command line R script for GNU `make` like functionality. Offers some convenience command line commands to facilitate package developement in R.
This project aims to substitute [makeR](https://github.com/tudo-r/makeR) sooner or later.

## Installation

To make use of `dt` put in in your `PATH` and make it executable. This can be done in the following way on Unix-Systems:
1) Clone the repository
2) Make a *symbolic link* (*symlink*) of the dt-file into your bin-directory, e.g. `$ ln -s ~/path-to-the-dt-repository/dt /usr/local/bin/`. Alternatively you can create a user-specific `~/bin` directory and place the symlink in it via `$ ln -s ~/path-to-the-dt-repository/dt ~/bin`.
3) Assure that you have installed all the required R-packages *methods*, *optparse*, *roxygen2*, *devtools*, *testhat* and *covr*. The latter is not released on CRAN until now. So the following instructions should be performed:

```splus
install.packages(c("methods", "optparse", "devtools", "roxygen2", "testthat")
devtools::install_github("jimhester/covr")
```

## Usage

Once `dt` is configured, you should be able to use it. Thus, just go into the root of a package's directory, type `dt` and confirm with the enter key. You should see a detailed overview of the available commands and a description of their effect.

## Contact

Please use the [issue tracker](https://github.com/tudo-r/dt/issues) for problems, questions and comments. 
