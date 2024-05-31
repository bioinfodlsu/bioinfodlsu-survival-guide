This is a jupyter book providing a collection of reference material for FAQ from members/applicants of Bioinformatics Lab, DLSU Manila.
It is hosted using Github Pages at: https://bioinfodlsu.com/bioinfodlsu-survival-guide/intro.html

For building, you need `Jupyter Book`. Get it, e.g. via conda:
```
conda install -c conda-forge jupyter-book
```

To build, inside the `bioinfodlsu-surviva-guide` directory, with the conda environment activated, run: 
```
jupyter-book build .
```
The home page for the book can be found at `_build/index.html`.


For deploying, you need to `ghp-import`. Get it, e.g. via conda:
```
conda install -c conda-forge ghp-import
```
To deploy, after a fresh build, run:
```
ghp-import -n -p -f _build/html
```
This will push the fresh html files to the `gh-pages` branch of this repository.
