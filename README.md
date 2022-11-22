rmr2
====

A package that allows R developer to use Hadoop MapReduce, developed as part of the RHadoop project. Please see the [RHadoop wiki](https://github.com/RevolutionAnalytics/RHadoop/wiki) for information. 

Change 2022-11: `rmr2` won't compile on Linux Mint 21 even with `Rcpp` installed because it is not linked to `Rcpp`. To work in R 4.2.x (tested on R 4.2.2), the DESCRIPTION file must contain `LinkingTo: Rcpp` (relevant [SO page](https://stackoverflow.com/questions/16259299/error-when-compiling-rcpp-code-in-an-r-package-using-rstudio)).

