# LNLS CS Studio Release

[![Build Status](https://travis-ci.org/lnls-sirius/lnls-studio.svg?branch=master)](https://travis-ci.org/lnls-sirius/lnls-studio)

### Building the release
In order to build the new release, switch to the branch with `git checkout` according with the desired version. Besides `master`, two other branches are available: `4.3.x` and `4.4.x`. Then, type in `mvn install` to compile and build the release, which will be saved in the folder `repository/target/products/cs-studio/`.

To use `mvn`, you must download Maven packages from your respective OS distribuition package repository.

Any doubts, problems or suggestions, please send an email to `gustavo.pinton@lnls.br` or `eduardo.coelho@lnls.br`.

Release products can be downloaded at http://csscon.lnls.br

### Product features

This product is composed of the following Control System's features

* BEAST Alarm Client Toolkit
* Databrowser2
* Olog and Logbook support
* BOY and Display Builder
* EDM2OPI
