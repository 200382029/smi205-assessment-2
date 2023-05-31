README for SMI205 Assessmnet 2
================
200382029
2023-05-22

-   [1. Replication report](#1-replication-report)
    -   [1.1. Your Workflow](#11-your-workflow)
    -   [1.2. Re-publishing data and
        code](#12-re-publishing-data-and-code)
-   [2. Rpubs version of the template](#2-rpubs-version-of-the-template)
-   [3. `renv` package](#3-renv-package)
    -   [3.1. How to work with `renv`
        package](#31-how-to-work-with-renv-package)
    -   [3.2. Trouble shooting with `renv`
        package](#32-trouble-shooting-with-renv-package)
-   [4. Transparency checklist](#4-transparency-checklist)
-   [5. My enviroment](#5-my-enviroment)

# 1. Replication report

The `SMI205_Assessment2_Template.Rmd` is enlisted within the repository
showing all steps taken including cod, graphs and descriptions. It
beings with workspace setup information such as libraries and
environment. The template then includes academic research regarding
similar issues and further followed with information regarding where and
how the data was installed and changes to variables. Outputs for each of
the three regressions are shown and then followed with regression models
and other outputs showing distrust in government and a conclusion
summarizing the findings.

The work has then been published as a reproducible report on
[Rpubs.com](https://rpubs.com/a200382029/1047951) website and an online
repository project was formed on Github.

## 1.1. Your Workflow

This workflow includes multiple folders: two readme files, the work
project, template and pre-registration form

## 1.2. Re-publishing data and code

Data has not been republished or created

# 2. Rpubs version of the template

HTML version of the template is published here:
<https://rpubs.com/a200382029/1047951>

# 3. `renv` package

The Template.Rproj was created without using `renv` package, yet, you
could consider using it. The `renv` package helps you to create a
reproducible environment for your R project. Read more here:
<https://rstudio.github.io/renv/>.

It saves information about R and loaded packages. So if you later (after
any R updates or changes in the packages) or other people open your
Rproj, it will install the same libraries, and will not use the central
libraries installed on a computer ([Joseph
2022](https://medium.com/@adrian.joseph/renv-make-r-environment-reproducible-414d88c683aa)).

## 3.1. How to work with `renv` package

-   Call `renv::init()` to initialise a new project-local environment
    with a private R library.
-   Call `renv::snapshot()` to save the state of the project library to
    the lockfile (called renv.lock).
-   Call `renv::restore()` to recall the packages and version the last
    time you called `renv::snapshot()`.

They are called automatically when you work in RProj and initiate `renv`
at the start.

## 3.2. Trouble shooting with `renv` package

This is a useful guide by Joseph A. (2022). renv: make R environment
reproducible. URL:
<https://medium.com/@adrian.joseph/renv-make-r-environment-reproducible-414d88c683aa>
(accessed 09/02/2023).

# 4. Transparency checklist

-   All relevant files have been organised and saved in folders
-   Are all files, variables and R objects have been named and organised
    (in the template folder)
-   A READme file has been included
-   This project has been tested to run on a different device
-   Information about your workspace specifications have been saved in
    your READme file
-   No sensitive information has been included in the Github

# 5. My enviroment

Below you can find information about versions of R and specific packages
used to create this project.

``` r
sessionInfo()
```

    ## R version 4.2.2 (2022-10-31 ucrt)
    ## Platform: x86_64-w64-mingw32/x64 (64-bit)
    ## Running under: Windows 10 x64 (build 19045)
    ## 
    ## Matrix products: default
    ## 
    ## locale:
    ## [1] LC_COLLATE=English_United Kingdom.utf8 
    ## [2] LC_CTYPE=English_United Kingdom.utf8   
    ## [3] LC_MONETARY=English_United Kingdom.utf8
    ## [4] LC_NUMERIC=C                           
    ## [5] LC_TIME=English_United Kingdom.utf8    
    ## 
    ## attached base packages:
    ## [1] stats     graphics  grDevices datasets  utils     methods   base     
    ## 
    ## loaded via a namespace (and not attached):
    ##  [1] compiler_4.2.2  fastmap_1.1.1   cli_3.6.1       htmltools_0.5.5
    ##  [5] tools_4.2.2     rstudioapi_0.14 yaml_2.3.7      rmarkdown_2.21 
    ##  [9] knitr_1.42      xfun_0.39       digest_0.6.31   rlang_1.1.1    
    ## [13] renv_0.17.3     evaluate_0.21
