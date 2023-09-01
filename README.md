rtracklayer
================
NULL [![License: Artistic-2.0 + file
LICENSE](https://img.shields.io/badge/license-Artistic--2.0%20+%20file%20LICENSE-blue.svg)](https://cran.r-project.org/web/licenses/Artistic-2.0%20+%20file%20LICENSE)
[![](https://img.shields.io/badge/devel%20version-1.61.1-black.svg)](https://github.com/lawremi/rtracklayer)
[![](https://img.shields.io/github/languages/code-size/lawremi/rtracklayer.svg)](https://github.com/lawremi/rtracklayer)
[![](https://img.shields.io/github/last-commit/lawremi/rtracklayer.svg)](https://github.com/lawremi/rtracklayer/commits/master)
<br> [![R build
status](https://github.com/lawremi/rtracklayer/workflows/rworkflows/badge.svg)](https://github.com/lawremi/rtracklayer/actions)
[![](https://codecov.io/gh/lawremi/rtracklayer/branch/master/graph/badge.svg)](https://app.codecov.io/gh/lawremi/rtracklayer)
<br>
<a href='https://app.codecov.io/gh/lawremi/rtracklayer/tree/master' target='_blank'><img src='https://codecov.io/gh/lawremi/rtracklayer/branch/master/graphs/icicle.svg' title='Codecov icicle graph' width='200' height='50' style='vertical-align: top;'></a>
<h4>  
README updated: <i>Sep-01-2023</i>  
</h4>

<!-- To modify Package/Title/Description/Authors fields, edit the DESCRIPTION file -->

## `rtracklayer`: R interface to genome annotation files and the UCSC genome browser

### Extensible framework for interacting with multiple genomebrowsers (currently UCSC built-in) and manipulatingannotation tracks in various formats (currently GFF, BED, bedGraph, BED15,WIG, BigWig and 2bit built-in). The user may export/import tracks to/from thesupported browsers, as well as query and modify the browser state, such as thecurrent viewport.

If you use `rtracklayer`, please cite:

<!-- Modify this by editing the file: inst/CITATION  -->

> M. Lawrence, R. Gentleman, V. Carey: “rtracklayer: an {R} package for
> interfacing with genome browsers”. Bioinformatics 25:1841-1842.

## Installation

``` r
if(!require("remotes")) install.packages("remotes")

remotes::install_github("https://github.com/lawremi/rtracklayer")
library(rtracklayer)
```

## Documentation

### [Website](https://lawremi.github.io/rtracklayer)

### [Get started](https://lawremi.github.io/rtracklayer/articles/rtracklayer)

<br>
