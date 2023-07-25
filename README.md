# Course for single-cell sequencing data analysis

This repository contains all instructions for the 2023 course for analysis of single-cell sequencing data.

## Directory Structure

* `scripts/` - Scripts used for the analysis
* `docs/` - Document files
* `data/` - Data (large, not included in **git**)
* `results/` - Analysis output (not included in **git**)
* `envs/` - **conda** environment YAML files
* `LICENSE` - The project license

## First Steps
> First, you need to install [conda](https://docs.conda.io/en/latest/). Then, open your terminal (Ubuntu: Alt+Ctrl+T, Windows: search for Powershell) and install git.
```
conda install -c conda-forge mamba # (this will only increase speed later on!)
mamba install -c anaconda git 
```
> Next, download and enter the repository.
```
git clone https://github.com/saliba-lab/course-scSeq-2023.git
cd course-scSeq-2023
```
> Afterwards install the necessary packages.
```
mamba env create -f envs/R.yml
```
> Then, activate your environment (the name is specified in the file envs/R.yml)
```
conda activate sc-seq-course
```

## Background
Here are references that provide background for the fundamentals or R as well as single-cell analysis.
### R and Data Science
- [Google Style Guide](https://google.github.io/styleguide/)
- [Tidyverse style guide](https://style.tidyverse.org/) by Hadley Wickham
- [R intro](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf) by the R core team
- [R for Data Science (R4DS))](https://r4ds.had.co.nz/) by Hadley Wickham
- [Introduction to Data Science](http://rafalab.dfci.harvard.edu/dsbook/) by Rafael Irizarry
- [Modern Statistics for Modern Biology](https://www.huber.embl.de/msmb/) by Wolfgang Huber

### Single-cell Analysis
- [Seurat](https://satijalab.org/seurat/)
- [Orchestrating Single-Cell Analysis](https://bioconductor.org/books/release/OSCA/) with Bioconductor
- [scanpy](https://scanpy.readthedocs.io/en/stable/) by the Theis lab
- [scVI-tools](https://scvi-tools.org/) by the Josef lab
