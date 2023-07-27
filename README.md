# R Code for the creation of the insect bite force database

This repository contains the R code that was used to create the tables and figures of the article describing the insect bite force database published under

Rühr et al. (**in review**): A bite force database of 654 insect species (preprint of earlier manuscript version available at [bioRxiv](https://doi.org/10.1101/2022.01.21.477193)).

## Instructions

1.  Open the R project 'Bite_Force_Database.Rproj'. We have used RStudio [1] to run R [2]
2.  Open the R script 'Bite_Force_Database.R'
3.  Run the script

The script contains comments that explain the code step-by-step.

The Zenodo folder that is automatically downloaded by the script is available at [doi.org/10.5281/zenodo.5782922](https://www.doi.org/10.5281/zenodo.5782922). Note that the Zenodo data must be unzipped after download so that all files are located in the same folder as the 'Bite_Force_Database.Rproj' file.

The Zenodo repository already contains all files that are produced by this script (mainly PDFs with plotted figures and the final database csv file 'iBite_table.csv'). Running this script will overwrite those files with the identical content again.

The exact code to produce the database and manuscript is stored under release [1.0.0.](https://github.com/Peter-T-Ruehr/InsectBiteForceDatabase/releases/tag/v1.0.0).

## References

[1] <https://www.rstudio.com/>

[2] R Core Team. R: A language and environment for statistical computing. R Foundation for Statistical Computing. (R Foundation for Statistical Computing, 2022).
