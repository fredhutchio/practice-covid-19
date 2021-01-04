# Practice data analysis in R - COVID-19

Rami Krispin's [tidy version of the Johns Hopkins global data](https://github.com/RamiKrispin/coronavirus)
is available in an R package,
`coronavirus`,
that is available for installation via CRAN using `install.packages("coronavirus")`.
Because package from CRAN is only updated periodically,
you can also install directly from the GitHub repository:

```
# install.packages("devtools")
devtools::install_github("RamiKrispin/coronavirus")```

## Example projects

**Rami Krispin developed a fantastic [Coronavirus dashboard](https://ramikrispin.github.io/coronavirus_dashboard/#summary) summarizing global data that is updated on a daily basis.**
Rami's approach uses [flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/) to create interactive summaries and visualizations.
The complete code for Rami's dashboard is available [here](https://github.com/RamiKrispin/coronavirus_dashboard);
look at [`index.Rmd`](https://github.com/RamiKrispin/coronavirus_dashboard/blob/master/index.Rmd) to see the R code creating the figures.
