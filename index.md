---
title: "R Documentation Task Force"
layout: page
output: 
  html_document:
    self_contained: no
---

# Overview

The R Documentation Task Force is an [R Consortium](https://www.r-consortium.org/)
Infrastructure Steering Committee supported project to design a new
documentation infrastructure for R.

The advantages of this new documentation system are:
1. Documentation can be created in many different methods and converted between them.
2. Documentation can be generated dynamically for functions returned as
   values from other functions.
3. Documentation can be de-coupled from the package system.


# Packages

[![parsetools](https://github.com/RDocTaskForce/parsetools/raw/master/man/figures/logo.png)](https://github.com/RDocTaskForce/parsetools) 
[![Build Status](https://travis-ci.org/RDocTaskForce/parsetools.svg?branch=master)](https://travis-ci.org/RDocTaskForce/parsetools) 
[![Coverage](https://codecov.io/github/RDocTaskForce/parsetools/coverage.svg?branch=master)](https://codecov.io/github/RDocTaskForce/parsetools?branch=master)[
![CRAN version](http://www.r-pkg.org/badges/version/parsetools)](https://cran.r-project.org/package=parsetools) 
[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)

Tools and utilities for dealing with parse data.  It includes tools for
extracting parse data cleaner than what is obtained from the
`utils::getParseData` function.  It also includes utilities for
subsetting the parse data and identifying different components and
structures.

[![`pkgcond`](https://github.com/RDocTaskForce/pkgcond/raw/master/man/figures/logo.png)](https://github.com/RDocTaskForce/pkgcond) 
[![Travis build status](https://travis-ci.org/RDocTaskForce/pkgcond.svg?branch=master)](https://travis-ci.org/RDocTaskForce/pkgcond)
[![Coverage status](https://codecov.io/gh/RDocTaskForce/pkgcond/branch/master/graph/badge.svg)](https://codecov.io/github/RDocTaskForce/pkgcond?branch=master)
[![CRAN version](http://www.r-pkg.org/badges/version/pkgcond)](https://cran.r-project.org/package=pkgcond)
[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)

A general purpose package [`pkgcond`](https://github.com/RDocTaskForce/pkgcond) 
facilitates the creation of errors, warnings,
and messages (collectively called signals or conditions) that are more informative
than the base versions.

Signals can be created through `pkg_error()`, `pkg_warning()` and `pkg_message()`.
When these are used a scope is computed and used to create errors, warnings and 
signals, respectively, with classes set to the combinations of the scope.
The scope, while is could be set explicitly, infers where the condition is created,
and will typically include the function call and package name.

[![`postlogic`](https://github.com/RDocTaskForce/postlogic/raw/master/man/figures/logo.png)](https://github.com/RDocTaskForce/postlogic) 
[![Build Status](https://travis-ci.org/RDocTaskForce/postlogic.svg?branch=master)](https://travis-ci.org/RDocTaskForce/postlogic)
[![Coverage](https://codecov.io/github/RDocTaskForce/postlogic/coverage.svg?branch=master)](https://codecov.io/github/RDocTaskForce/postlogic?branch=master)
[![CRAN version](http://www.r-pkg.org/badges/version/postlogic)](https://cran.r-project.org/package=postlogic)
[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

Postlogic add postfix logic opperators `%if%` and `%unless%` for 
convenience.  This is used in other RDTF packages primarily for 
conditioning verbose messages.

[![`testextra`](https://github.com/RDocTaskForce/testextra/raw/master/man/figures/logo.png)](https://github.com/RDocTaskForce/testextra) 
[![Build Status](https://travis-ci.org/RDocTaskForce/testextra.svg?branch=master)](https://travis-ci.org/RDocTaskForce/testextra)
[![Coverage](https://codecov.io/github/RDocTaskForce/testextra/coverage.svg?branch=master)](https://codecov.io/github/RDocTaskForce/testextra?branch=master)
[![CRAN version](http://www.r-pkg.org/badges/version/testextra)](https://cran.r-project.org/package=testextra)
[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)

The [`testextra`](https://github.com/RDocTaskForce/testextra) package 
provides the support for embedding [`testthat`](https://cran.r-project.org/package=testthat)
compatible tests in source code through special testing blocks.

```r
if(FALSE){#@testing An optional description
    # place tests in a block such as this and they will be extracted
    # to the ./tests/testthat folder when extract_tests() is run.
}
```

[![`Rd`](https://github.com/RDocTaskForce/Rd/raw/master/man/figures/logo.png)](https://github.com/RDocTaskForce/Rd) 
[![Travis build status](https://travis-ci.org/RDocTaskForce/Rd.svg?branch=master)](https://travis-ci.org/RDocTaskForce/Rd) 
[![Coverage status](https://codecov.io/gh/RDocTaskForce/Rd/branch/master/graph/badge.svg)](https://codecov.io/github/RDocTaskForce/Rd?branch=master)
[![CRAN version](http://www.r-pkg.org/badges/version/Rd)](https://cran.r-project.org/package=Rd)
[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)

The [`Rd`](https://github.com/RDocTaskForce/Rd) package extends the base 
utilities in the `tools` and `utils` package to facilitate creation, 
checking and manipulation of R documentation (Rd) objects in code.
It is similar in functio and usage to the [`htmltools`](https://cran.r-project.org/package=htmltools)
package.

[![`extendedRef`](https://github.com/RDocTaskForce/extendedRef/raw/master/man/figures/logo.png)](https://github.com/RDocTaskForce/extendedRef)
[![Travis build status](https://travis-ci.org/RDocTaskForce/extendedRef.svg?branch=master)](https://travis-ci.org/RDocTaskForce/extendedRef)
[![Coverage status](https://codecov.io/gh/RDocTaskForce/extendedRef/branch/master/graph/badge.svg)](https://codecov.io/github/RDocTaskForce/extendedRef?branch=master)
[![CRAN version](http://www.r-pkg.org/badges/version/extendedRef)](https://cran.r-project.org/package=extendedRef)
[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

The [`extendedRef`](https://github.com/RDocTaskForce/extendedRef) package
adds private variables, static variables, and static methods to 
reference classes.

## [`documentation`](https://github.com/RDocTaskForce/documentation) 
[![Travis build status](https://travis-ci.org/RDocTaskForce/documentation.svg?branch=master)](https://travis-ci.org/RDocTaskForce/documentation)
[![Coverage status](https://codecov.io/gh/RDocTaskForce/documentation/branch/master/graph/badge.svg)](https://codecov.io/github/RDocTaskForce/documentation?branch=master)
[![CRAN version](http://www.r-pkg.org/badges/version/documentation)](https://cran.r-project.org/package=documentation)
[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

The core of the new documentation infrastructure. This package contains
the classes for documentation encapsulation as well as methods for
creation of documentation objects and formatting.  While the class 
system is maturing, what is and is not included in this package versus
independent packages is still in flux.
