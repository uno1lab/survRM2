# survRM2 version 1.0-5 (2026-11)
### Maintenance
* Fixed the YAML header of the vignette so that it re-builds with recent versions of pandoc.
* Added an `Authors@R` field to DESCRIPTION.
* Replaced the deprecated `@docType package` with `"_PACKAGE"` in the package documentation and added `Encoding: UTF-8` to DESCRIPTION.


# survRM2 version 1.0-4 (2022-06)
### Minor improvements
* Fixed a bug in the initial check on `tau` in the rmst2 function.


# survRM2 version 1.0-3 (2020-06)
### Minor improvements
* Updated the code for checking a specified `tau` to allow such a tau that is greater than the last event time when the KM curve reaches 0 at that time point.
* Updated the code to improve the execution time for RMST analysis with covariates. 
* Fixed the code to handle large data (>100K observations). 
* Fixed the code to accept general arguments for plots (e.g., `xlim` and `ylim`) in `plot.rmst2()` function.


# survRM2 version 1.0-2 (2017-02)
### Minor improvements
* Changed the default value of `tau` in `rmst2()`. When `tau = NULL`, the default value (i.e., the minimum of the largest observed time in each of the two groups) is now used.
* Fixed to reflect an `alpha` argument in `rmst2()`.

# survRM2 version 1.0-1 (2015-02)
* Initial release
