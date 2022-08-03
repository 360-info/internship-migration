# Migration's Changing Face

The project attempts to raise the awareness of illegal and trafficked migrants for the public on International Refugees Day. Visualisations on migrants will be focused on discovering two aspects, missing migrants, and human trafficking overtime. 

![Code in analysis-missing_migrants.qmd](out/figures/migrantsheatmap.png)

![Code in analysis-human_trafficking.qmd](out/figures/victimflows.png)

![Code in analysis-human_trafficking.qmd](out/figures/victimdistributions.png)

## Use + Remix rights

![[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0)](https://mirrors.creativecommons.org/presskit/buttons/80x15/png/by.png)

These charts, as well as the analyses that underpin them, are available under a Creative Commons Attribution 4.0 licence. This includes commercial reuse and derivates.

<!-- Do any of the data sources fall under a different licence? If so, describe the licence and which parts of the data fall under it here! if most of it does, change the above and replace LICENCE.md too -->

Data in these charts comes from:

- [Missing Migrants Project](https://missingmigrants.iom.int/) 
- [Counter Trafficking Data Collaborative](https://www.ctdatacollaborative.org/dataset/resource/511adcb7-b1a2-4cc7-bf2f-0960d43a49cc) 

**Please attribute 360info and the data sources when you use and remix these visualisations.**

## Get the graphics

If you just need the versions of the graphics we've produced, they're in the [`out/figures` folder](./out/figures).

## Reproduce the analysis

Theis analysis is done in [R](https://r-project,.org). To reproduce it, you'll need to:

- [Download the install R](https://www.r-project.org)
- Satisfy the R package dependencies. In R:
  * Install the [`renv`](https://rstudio.github.io/renv) package with `install.packages("renv")`,
  * Then run `renv::restore()` to install the R package dependencies.
  * (For problems satisfying R package dependencies, refer to [Quarto's documentation on virtual environments](https://quarto.org/docs/projects/virtual-environments.html).)

Now, render the `.rmd` files to the `/docs` directory with:

```sh
rmarkdown::render("report-migration.Rmd")
```

The figures are generated to the [`out/figures` folder](./out/figures). You can 

## Help

<!-- replace `report-template` with the name of this repo in the link below  -->

If you find any problems with our analysis or charts, please feel free to [create an issue](https://github.com/360-info/internship-migration/issues/new)!

