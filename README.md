# Introduction to *p*-value functions

This repository contains all files for the presentation for my introduction to *p*-value functions at the university of Zürich on October 1st 2025.

The presentation is based on [Quarto](https://quarto.org/) and [revealjs](https://quarto.org/docs/presentations/revealjs/). It is rendered as a HTML file.

The R code included in the presentation is accessible through the source file (.qmd) or the presentation itself (klick "Code" to expand the code chunks).

My R package `pvaluefunctions` is available on [CRAN](https://cran.r-project.org/package=pvaluefunctions). Alternatively, it can be installed directly from the [GitHub repository](https://github.com/DInfanger/pvaluefunctions) using the `devtools` package:

```{r}
library(devtools)
install_github(DInfanger/pvaluefunctions)
```

For more information about *p*-value functions, I recommend reading our [introductory paper](https://doi.org/10.1002/sim.8293) on the topic:

Infanger D, Schmidt-Trucksäss A. (2019): P value functions: An underused method to present research results and to promote quantitative reasoning. *Stat Med.* 38, 4189-4197. doi: [10.1002/sim.8293](https://doi.org/10.1002/sim.8293).
