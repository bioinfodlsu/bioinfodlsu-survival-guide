# Bioinformatics Lab Survival Guide
[![Build and deploy Jupyter book](https://github.com/bioinfodlsu/bioinfodlsu-survival-guide/actions/workflows/build-and-deploy.yml/badge.svg)](https://github.com/bioinfodlsu/bioinfodlsu-survival-guide/actions/workflows/build-and-deploy.yml)

This is a jupyter book providing a collection of reference material for FAQ from members/applicants of Bioinformatics Lab, DLSU Manila.
It is hosted using Github Pages at: https://bioinfodlsu.com/bioinfodlsu-survival-guide/intro.html

## Building locally
You need `Jupyter Book`. Get it, e.g. via conda:
```
conda install -c conda-forge jupyter-book
```

To build, inside the `bioinfodlsu-survival-guide` directory, with the conda environment activated, run: 
```
jupyter-book build .
```
The home page for the book can be found at `_build/index.html`.

## Deploying
Github Actions workflow has been configured so that a push to main automatically builds and deploys to the site above.
Be sure to have checked the build locally before issuing a pull request.
