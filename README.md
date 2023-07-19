# Research compendium

This is an example of a research compendium. It contains the instructions for data analysis in a structured and reproducible way.

## Directory Structure

* `bin/` - Scripts used for the analysis
* `docs/` - Document files
* `data/` - Data output (large, not included in **git**)
* `workflows/` - Workflows executing scripts in **bin/**
* `reports/` - Reports for exploratory analysis
* `analysis/` - Analysis output (not included in **git**)
* `envs/` - **conda** environment YAML files
* `LICENSE` - The project license

## First Steps
> First, install the necessary packages
```
mamba env create -f envs/R.yml
```
> Then, activate your environment (the name is specified in the file envs/R.yml)
```
conda activate my-first-project
```
