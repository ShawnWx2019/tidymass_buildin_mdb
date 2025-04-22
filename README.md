
<!-- README.md is generated from README.Rmd. Please edit that file -->

# `{buildmdb}`

<!-- badges: start -->
<!-- badges: end -->

## Installation

You can install the development version of `{buildmdb}` like so:

``` r
# FILL THIS IN! HOW CAN PEOPLE INSTALL YOUR DEV PACKAGE?
```

## Run

You can launch the application by running:

``` r
buildmdb::run_app()
```

## About

You are reading the doc about version : 1.0.0

This README has been compiled on the

``` r
Sys.time()
#> [1] "2025-04-22 22:37:36 CST"
```

Here are the tests results and package coverage:

``` r
devtools::check(quiet = TRUE)
#> ℹ Loading buildmdb
#> Loading required package: metid
#> Warning in fun(libname, pkgname): mzR has been built against a different Rcpp version (1.0.11)
#> than is installed on your system (1.0.14). This might lead to errors
#> when loading mzR. If you encounter such issues, please send a report,
#> including the output of sessionInfo() to the Bioc support forum at 
#> https://support.bioconductor.org/. For details see also
#> https://github.com/sneumann/mzR/wiki/mzR-Rcpp-compiler-linker-issue.
#> metid 1.3.1 (2025-04-20 06:21:18.006509)
#> 
#> Attaching package: 'metid'
#> 
#> The following object is masked _by_ 'package:massdataset':
#> 
#>     check_mass_dataset
#> 
#> The following object is masked _by_ 'package:masstools':
#> 
#>     remove_noise
#> 
#> The following object is masked from 'package:stats':
#> 
#>     filter
#> ── R CMD check results ───────────────────────────────────── buildmdb 1.0.0 ────
#> Duration: 52.2s
#> 
#> ❯ checking data for non-ASCII characters ... WARNING
#>     Error loading dataset 'gnps_ms2':
#>      Error in .requirePackage(package) : 
#>       unable to find required package 'metid'
#>     
#>     Error loading dataset 'hmdb_ms2':
#>      Error in .requirePackage(package) : 
#>       unable to find required package 'metid'
#>     
#>     Error loading dataset 'massbank_ms2':
#>      Error in .requirePackage(package) : 
#>       unable to find required package 'metid'
#>     
#>     Error loading dataset 'mona_ms2':
#>      Error in .requirePackage(package) : 
#>       unable to find required package 'metid'
#>     
#>     The dataset(s) may use package(s) not declared in Depends/Imports.
#> 
#> ❯ checking LazyData ... WARNING
#>     LazyData DB of 223.4 MB without LazyDataCompression set
#>     See §1.1.6 of 'Writing R Extensions'
#> 
#> ❯ checking installed package size ... NOTE
#>     installed size is 239.5Mb
#>     sub-directories of 1Mb or more:
#>       data  239.4Mb
#> 
#> ❯ checking for future file timestamps ... NOTE
#>   unable to verify current time
#> 
#> ❯ checking top-level files ... NOTE
#>   Non-standard file/directory found at top level:
#>     ‘dev’
#> 
#> ❯ checking dependencies in R code ... NOTE
#>   Namespaces in Imports field not imported from:
#>     ‘config’ ‘golem’ ‘shiny’
#>     All declared Imports should be used.
#> 
#> 0 errors ✔ | 2 warnings ✖ | 4 notes ✖
#> Error: R CMD check found WARNINGs
```

``` r
covr::package_coverage()
#> Error in loadNamespace(x): there is no package called 'covr'
```
