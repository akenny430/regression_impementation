# Linear regression implementation

This repo contains code as part of our
([Aiden](https://www.linkedin.com/in/akenny430/) and [Thu](https://www.linkedin.com/in/thuhdo/))
final project for MAT338: Computational Mathematics, at Franklin & Marshall College.

The project sought to implement linear regression
using a
[QR decomposition computed with Householder transformations](https://en.wikipedia.org/wiki/QR_decomposition#Using_Householder_reflections).
The implementation was written in `C++`,
with bindings then written for use in an `R` library,
making use of the
[`Rcpp`](https://cran.r-project.org/web/packages/Rcpp/index.html) package.

Code for the implmentation and package
can be found in the `pck338` directory.
The final results and presentation (a report and slides)
can be found in the `docs` directory.
Unfortunately, the LaTeX files used to generate these
have been lost to time.
Examples of how to use the library can be found in the report.
