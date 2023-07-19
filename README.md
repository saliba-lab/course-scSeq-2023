# Course for single-cell sequencing data analysis

This repository contains all instructions for the 2023 course for analysis of single-cell sequencing data.

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
