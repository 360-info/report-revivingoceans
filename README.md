# Reviving oceans

Visualises reported fishing catch globally over the last 70 years, as well as estimate sof illegal fishing and discarded fish.

![Industrial-kg_reported_persqkm-1950-1954](https://user-images.githubusercontent.com/6520659/172083579-152824ec-864d-4fa2-ba97-7b5935a273ca.png)

## Use + Remix rights

![[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0)](https://mirrors.creativecommons.org/presskit/buttons/80x15/png/by.png)

These charts, as well as the analyses that underpin them, are available under a Creative Commons Attribution 4.0 licence. This includes commercial reuse and derivates.

<!-- Do any of the data sources fall under a different licence? If so, describe the licence and which parts of the data fall under it here! if most of it does, change the above and replace LICENCE.md too -->

Data in these charts comes from:

* [Global Fisheries Landings V4.0](https://metadata.imas.utas.edu.au/geonetwork/srv/api/records/5c4590d3-a45a-4d37-bf8b-ecd145cb356d). The accompanying paper is [Watson (2017)](https://www.nature.com/articles/sdata201739).

**Please attribute 360info and the data sources when you use and remix these visualisations.**

## Add the interactive to your story

If you just want to add the interactive to your story, copy the following embed code and paste it into your editor:

```html
<iframe
  src="https://360info-revivingoceans.pages.dev/globalfishmap.html"
  title="Measure of reported and illegal fishing, as well as discarded fish since 1950. Data comes from the Global Fisheries Landings v4 dataset."
  width="500"
  height="670"
  scrolling="no"
  style="border:none;">
</iframe>
```

## Reproduce the analysis

We typically publish graphics using [Quarto](https://quarto.org) notebooks, which can be found in the`*.qmd` files. Quarto allows reproducible analysis and visualisation to be done in a mix of languages, but we typically use [R](https://r-project,.org) and [Observable JS](https://observablehq.com/@observablehq/observables-not-javascript).

You'll need to:
- [Download and install Quarto](https://quarto.org/docs/get-started)
- [Download the install R](https://www.r-project.org)
- Satisfy the R package dependencies. In R:
  * Install the [`renv`](https://rstudio.github.io/renv) package with `install.packages("renv")`,
  * Then run `renv::restore()` to install the R package dependencies.
  * (For problems satisfying R package dependencies, refer to [Quarto's documentation on virtual environments](https://quarto.org/docs/projects/virtual-environments.html).)

Now, render the `.qmd` files to the `/out` directory with:

```sh
quarto render
```

## Help

<!-- replace `report-template` with the name of this repo in the link below  -->

If you find any problems with our analysis or charts, please feel free to [create an issue](https://github.com/360-info/report-template/issues/new)!
