# SimultaneousCountModel_vignette

This repository contains a vignette illustrating the "simultaneous count model" approach from [*Simultaneous‐count models to estimate abundance from counts of unmarked individuals with imperfect detection*, Conservation Biology 33(3) 697—708, G.E. Ryan et al. 2019.]( https://doi.org/10.1111/cobi.13261) (Code for that paper is at [this repository](https://github.com/geryan/simultaneous_count_models))

A [pdf of this vignette](https://github.com/geryan/SimultaneousCountModel_vignette/blob/master/simultaneous_count_model_vignette.pdf) illustrates the model and shows the results output. Best downloaded to view.

To run through the vignette analyses yourself, use the [R-markdown file `scm_vignette.Rmd`](https://github.com/geryan/SimultaneousCountModel_vignette/blob/master/scm_vignette.Rmd). You must use RStudio with the R-markdown file. (More on R-markdown files [here](https://rmarkdown.rstudio.com).)

A [rendered html version](https://github.com/geryan/SimultaneousCountModel_vignette/blob/master/simultaneous_count_model_vignette.html) is also available. *You might not be able to knit the Rmd file successfully* because the large amout of JAGS output while the model is fitting seems to cause `knitr` it to freeze. So you may not be able to successfully recreate these rendered pdf and html files from your Rmd file, however you should be able to complete the analyses without a problem.
