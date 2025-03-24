
<!-- README.md is generated from README.Rmd. Edit ONLY this file if you need to make a change in README.md. But, after you edit it, you run `rmarkdown::render("README.Rmd")` in order to create the new README.md, which is the thing which is actually used. Must be a better way of doing this! -->

# Positron Tutorials

<!-- badges: start -->

[![R build
status](https://github.com/PPBDS/positron.tutorials/workflows/R-CMD-check/badge.svg)](https://github.com/PPBDS/positron.tutorials/actions)
<!-- badges: end -->

## About this package

**positron.tutorials** is a collection of tutorials for working with
Positron. Covers scripts, Quarto documents, git, Github, and Quarto
websites. Makes extensive use of the tools in the
**[tutorial.helpers](https://ppbds.github.io/tutorial.helpers/)**
package.

## Installation

To install the package from CRAN:

``` r
install.packages("positron.tutorials")
```

You can install the development version from
[GitHub](https://github.com/) with:

``` r
remotes::install_github("PPBDS/positron.tutorials")
```

**positron.tutorials** is currently not avaible on CRAN.

## Tutorials

There are sevene tutorials in the package. In paratheses after the title
of the tutorial, we show the code for running the tutoria. Example:

    learnr::run_tutorial(name = "01-code", 
                         package = "positron.tutorials")

- *Positron and Code* (“01-code”). Introduce students to Positron and to
  writing R code in simple scripts.

- *Positron and Quarto* (“02-quarto”). Demonstrate more tricks for
  working with R code using Positron, and also explain Quarto documents.

- *Terminal* (“03-terminal”). Teach the command line.

- *Positron and GitHub Introduction* (“04-github-1”). Explain the basics
  of Git and GitHub, mostly in the context of Positron.

- *Positron and GitHub Advanced* (“05-github-2”). Provide more practice
  in working with Git/GitHub, including more details on the use of
  GitHub Pages.

- *Quarto Websites Introduction* (“06-websites-1”). Demonstrate the
  basics of website construction using Quarto projects.

- *Quarto Websites Advanced* (“07-websites-2”). Practice Quarto
  websites, with a focus on splitting data analysis tasks into separate
  files.
