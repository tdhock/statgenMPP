# statgenMPP 1.0.1.1

* Internal fix. No user visible changes.

# statgenMPP 1.0.1

* The logic in the scan process is improved, leading to much lower computation times. * Computations can now be done in parallel by registering a parallel back-end and setting `parallel = TRUE` in the `selQTLMPP` function.
* It is now possible to include a polygenic effect in the models to correct for background genetic information.
* A new function `createGDataMPP` is added to directly create a `gDataMPP` object from an `IBDprob` object (as created by `statgenIBD`) and a data.frame with phenotypic data.
* `readRABBIT` is renamed to `readRABBITMPP` to prevent future conflicts with a similar function in `statgenIBD`
* The trait column in the example data is renamed from "pheno" to "yield".

# statgenMPP 1.0.0

* Initial CRAN release
