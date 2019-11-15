# SimultaneousCountModel_vignette

This repository contains a vignette illustrating the "simultaneous count model" approach from [*Simultaneous‐count models to estimate abundance from counts of unmarked individuals with imperfect detection*, Conservation Biology 33(3) 697—708, G.E. Ryan et al. 2019.]( https://doi.org/10.1111/cobi.13261)

A [pdf of the vignette](https://github.com/geryan/SimultaneousCountModel_vignette/blob/master/simultaneous_count_model_vignette.pdf) illustrates the model and shows the results output. Best downloaded to view. (More on R-markdown files [here](https://rmarkdown.rstudio.com).)

To run through the analysis yourself, use the [R-markdown file `scm_vignette.Rmd`](https://github.com/geryan/SimultaneousCountModel_vignette/blob/master/scm_vignette.Rmd). you must use RStudio with the R-markdown file.

A [rendered html version](https://github.com/geryan/SimultaneousCountModel_vignette/blob/master/simultaneous_count_model_vignette.html) is also available. *You might not be able to knit the Rmd file successfully* because the large amout of JAGS output while the model is fitting seems to cause `knitr` it to freeze. So you may not be able to successfully recreate these rendered pdf and html files from your Rmd.
