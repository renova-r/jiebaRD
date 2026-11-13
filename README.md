# jiebaRD

Data files (dictionaries, HMM model, IDF weights, stop words) required by the jiebaR Chinese text segmentation package.

Compatibility updates by Renova.

Version 0.1.9001 only changes `DESCRIPTION` metadata: the description sentence is reworded, an `Authors@R` entry equivalent to the existing author and maintainer is added, and the stale optional `Date` field is removed. The dictionary data files are unchanged.

## Install

```r
install.packages("jiebaRD", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/jiebaRD@renova-0.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

jiebaRD is by Qin Wenfeng (maintainer); the original project is at <https://github.com/qinwf/jiebaRD/>. The dictionaries are the CppJieba data used by jiebaR (<https://github.com/aszxqw/cppjieba>). License: MIT + file LICENSE; see [LICENSE](LICENSE) (Copyright 2014-2015 Qin Wenfeng) and [LICENSE.md](LICENSE.md) (full MIT text).
