# Overview

The folder structure for our data analysis project (using BibTex, R, Quarto, and GitHub) is arranged like so: code, data, products, and results. Please have word processing software installed as well. See the readme.md files in each subdirectory for more information. **Please do not render any qmd files except for `Manuscript2.qmd` within the *products* subdirectory, as this causes the creation of extraneous files**.

## Code

The *code* folder contains subdirectories for data cleaning/preprocessing (processing) and analysis (analysis). Run `processingfile_v1.qmd` first, then `exploratory_analysis.qmd`, then `statistical_analysis.qmd`.

## Data

The *data* folder contains subdirectories for raw data and cleaned data.

## Products

The *products* folder contains manuscript itself and tables & plots in images file pertinent to our manuscript output. After running all scripts as listed in the code above, `Manuscript2.qmd` can be rendered to produce the final manuscript.

## Results

The *results* folder contains tables and graphs generated from exploratory data analysis and statistical analysis.
