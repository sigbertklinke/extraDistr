## Test environments

* Ubuntu

## Resubmission of orphaned package
This is a resubmission to take over maintenance of the orphaned 'extraDistr' package.

## Fixes
* Forked from twolodzko/extraDistr  not CRAN
* Updates DESCRIPTION, NEWS.md, README.md
* Fixed '@docType Packages' warning
* Fixed permanently moved URL in man/NegHyper.Rd as requested by the automated pre-test.
* Removed X-CRAN fields from DESCRIPTION to resolve database conflicts.

## R CMD check results
* Local R CMD check (Ubuntu 22.04.5): 1 NOTE (Maintainer change conflict).
* win-builder: 1 NOTE (Maintainer change conflict).

The 'Maintainer' conflict is expected as I am taking over the orphaned package.
The installed size (30MB) is due to the large number of distributions 
implemented via Rcpp/RcppArmadillo.