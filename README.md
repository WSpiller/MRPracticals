# MRPracticals

The `MRPracticals` R package provides necessary information for MR course practical sessions. It requires R version 3.4 and R Studio
for processing vignette files.

Information for two separate pratical sessions is currently included, pertaining to:

1. MR Base
2. The Radial MR package

## Installation

To install `MRPracticals` directly from the GitHub repository, first make sure you have the `devtools` package installed:

    install.packages("devtools")

Then the `MRPracticals` package can be installed using:

    library(devtools)
    install_github("WSpiller/MRPracticals",build_opts = c("--no-resave-data", "--no-manual"))
    
To update the package just run the `install_github("WSpiller/MRPracticals", build_opts = c("--no-resave-data", "--no-manual"))` command again.

## Description

The `MRPracticals` package contains a sample data frame, and two vignette files with code and instructions:

1. Running the command `vignette("MRBase")` will display a document giving a detailed description of the MR Base practical.

1. Running the command `vignette("RadialMR")` will display a document giving a detailed description of the RadialMR practical.

## Acknowledgments

This package contains material from the MR course, conducted at the University of Bristol.

## License

This project is licensed under GNU GPL v2.




