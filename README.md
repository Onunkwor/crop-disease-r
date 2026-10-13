# Analysing Crop Disease Data in R

A free, self-paced course for Nigerian plant-science students, built on real Nigerian crop data. Live at https://onunkwor.github.io/crop-disease-r/

| Lesson | Topic |
|---|---|
| 1 | Reading disease data: incidence, severity, and where the infection came from |
| 2 | How epidemics grow: the logistic curve, the t = 0 check, and fitting real data |
| 3 | Checking your own results: is a difference real, and what did the survey miss? |

The website is built with [Quarto](https://quarto.org) from the `.qmd` files here.

## Build the site

```
quarto render
```

The site appears in `_site/`.

## Data

- `data/cassava_mosaic_survey.xlsx`: Eni, Efekemo, Onile-ere and Pita (2021), Mendeley Data, [doi:10.17632/mpj2nxk3tk.1](https://doi.org/10.17632/mpj2nxk3tk.1), CC BY 4.0, used unmodified.
- `data/bean_week6.csv`: week-6 measurements from Raphael Odera Onunkwor's bean trial at Bells University of Technology; full reanalysis at [github.com/Onunkwor/pvfta1-phenology](https://github.com/Onunkwor/pvfta1-phenology).

## Licence

Text: CC BY 4.0. Code: MIT. See `LICENSE`.
