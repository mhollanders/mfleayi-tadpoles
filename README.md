# Data, analysis, and manuscript for "High chytrid prevalence and infection intensities in tadpoles of *Mixophyes fleayi*"

This repository contains the following folders related to this research article.

  - `analysis`: folder containing the Quarto document which contains all data wrangling, model fitting, and figure creation.
  - `data`: folder containing data files used in the analysis.
    - `lengths.csv`: file with body lengths (from nose tip to base of tail) measured in callipers (`length`), and mouthpart width measured in pixels in Adobe Photoshop (`mouth`)
    - `tadpole-data.csv`: file containing tadpole data with water and air temperatures, body length in mm, mouthpart width in pixels, average *Bd* load summarised from swam samples and accounting for qPCR dilution, mouthpart loss score of the top and bottom jaw sheaths and tooth rows, and the raw outcomes of duplicate qPCR runs.
    - `tadpole-length.csv`:  additional tadpole lengths from Brindle Creek measured in pixels in Adobe Photoshop and converted to mm to create Figure 1 (`figs/fig-lengths-brindle.png`)
  - `figs`: folder containing figures using in the manuscript, created in `analysis/tadpoles-analysis.qmd`.
  - `manuscript`: folder containing the Quarto dcoument of the manuscript and knitted pdf, reference file, and reference formatting file.
  - `mcmc`: model fit objects of the two models fit in `analysis/tadpoles-analysis.qmd`.
