# civis.political.r.training
A (very) lightweight R package for the "Introduction to Data Munging and Visualization in R" session at the Civis 2019 Political Community Summit.

This package can be installed in R and RStudio. First, make sure to have the [`remotes`](https://remotes.r-lib.org/) package installed:

```r
install.packages("remotes")
```

Then, run the following command in RStudio to install the `civis.political.r.training` package:

```r
remotes::install_github("civisanalytics/civis_political_r_training",
                        build = TRUE,
                        build_opts = c("--no-resave-data", "--no-manual"))
```

The training materials exist as a vignette within the `civis.political.r.training` package. To view them after installing the package, run the following command in RStudio:

```r
vignette("training", package = "civis.political.r.training")
```

Happy learning!
