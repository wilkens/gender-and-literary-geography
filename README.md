# Gender and literary geography

## About this repo

Code and data in support of [Elizabeth F. Evans](https://wayne.edu/people/gz0955) and [Matthew Wilkens](https://infosci.cornell.edu/content/wilkens), [_Gender and Literary Geography_](https://www.cambridge.org/core/elements/abs/gender-and-literary-geography/911FD1826C98AEAF6A12F42F05466788), Cambridge UP, 2025.

The results, visualizations, and analyses contained in the repository are a superset of those reported in the book. We've included additional material both to provide greater depth and context for the published results, and because there are some interesting findings that we think others may want to pursue.

## Files and directories

### `./notebook.ipynb`

This Jupyter notebook contains all of our analysis code. If you want to see how we calculated a result or produced a visualization, you should consult this notebook. You can reproduce all of our results by running the notebook in full. Note that the maps require a Mapbox API key.

If GitHub has trouble rendering the notebook -- and you don't want to run it locally -- you can view a [rendered copy](https://nbviewer.org/github/wilkens/gender-and-literary-geography/blob/main/notebook.ipynb) via nbviewer.

### `datasets/`

Input data is in this directory, except for three large datasets that are too big for GitHub (and are fetched directly from Figshare in the code). For reused datasets, links to the original versions are included in the notebook.

### `figures/`

All visualizations, in PNG and PDF formats. There are substantially more of these than are included in the book. For full definitions of the variables included, see the notebook.

### `results/`

Numerical results calculated form our input data, including statistical analyses. Brief versions of many of these are included in the notebook, but the full outputs are in this directory. Also includes derived datasets that can be reproduced by executing the full notebook (including the slow steps), or loaded as-is to save execution time if the underlying data have not changed.

If you just want to use our feature data for your own project, the easiest thing to do is to use one of the `all-features-*.csv.gz` files in this directory.