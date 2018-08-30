# ChIP-seq processing pipeline
An [R](https://www.r-project.org/) package for analysis of ChIP-seq and other functional sequencing data.
Please see [package homepage](http://compbio.med.harvard.edu/Supplements/ChIP-seq/) for details.

## Requirements
A unix-flavored OS with R and [Boost C++](https://www.boost.org/) installed.

## Installation
You can use devtools to install SPP:
```
require(devtools)
devtools::install_github('yanwu2014/spp', build_vignettes = FALSE)
```

Note: if Boost libraries are installed in a non-standard location, please specify the location in a `BOOST_ROOT` environment variable prior to running the installation.
```
export BOOST_ROOT=/path/boost_1_58_0/
```
