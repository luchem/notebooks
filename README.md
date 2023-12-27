[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/luchem/notebooks/HEAD)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![ruff](https://github.com/luchem/notebooks/actions/workflows/ruff.yml/badge.svg)](https://github.com/luchem/notebooks/actions/workflows/ruff.yml)

# Open Archive of Educational Chemistry Notebooks

An open collection of educational Jupyter Notebooks relevant to chemistry.
The notebooks can e.g. exemplify how to use a theory, process experimental data, or
visualise data. It can also be tutorials, labs, etc.

## Getting started

We recommend to install
[Anaconda](https://www.anaconda.com/) or the much smaller
[Miniforge](https://github.com/conda-forge/miniforge).
For the latter, the following installs all dependencies and starts
[JupyterLab](https://jupyter.org) in a web-browser:
~~~ bash
conda env create -f environment.yml # done only once
source activate luchem
jupyter-lab
~~~

## Topics

### General Chemistry

- [Data wrangling](general/data_wrangling.ipynb)
  Example of how to extract HTML tables into Python
- [Reaction balance](general/reaction_balance.ipynb).
  Balancing chemical reactions using linear algebra.
- [Reaction order](general/kinetics_reaction_order.ipynb).
  Determine reaction order from kinetic data.
- [Polyprotic Acid](general/polyprotic_acid.ipynb).
  General equilibrium calculations for arbitrary polyprotic-acids.

### Physical Chemistry

- [Acetone-Chloroform Mixture](physical/acetone_chloroform.ipynb).
  Activities and activity coefficients in an acetone-chloroform mixture.
- [Bragg-Williams Mixing](physical/bragg_williams.ipynb).
  Interactive plot of vapor pressures over a two-component, non-ideal mixture.
- [Claysius-Clapeyron](physical/clausius_clapeyron.ipynb).
  Applications of the Clausius-Clapeyron equation. E.g. linear regression on (_p,T_) data.
- [Equilibrium Reactions](physical/equilibrium_reactions.ipynb)
- [Haber-Bosch process](physical/haber_process.ipynb).
  Numerical integration of _H_ and _S_ to find temperature dependent eq. constant.
- [Heat Capacity](physical/heat_capacity.ipynb)
- [Mixing Entropy](physical/mixing_entropy.ipynb).
  Solved exercise illustrating mixing entropy and free energy of gases and mixtures.
- [Molecular partition functions](physical/molecular_partition_function.ipynb).
  Exploration of various molecular partition functions, e.g. rotation;
  vibrational; two-level systems. This also illustrates the use of symbolic algebra
  and interactive plots.
- [Polymer Collapse](physical/polymer_collapse.ipynb).
  Partition function of a collapsing polymer. 

## Contributing

Contributions are very welcome and done in the following steps:

1. Make a fork/branch of this repository
2. Add files and update `Topics` in this `README.md` file
3. Submit a pull-request (PR)
4. Await review

### Dependencies

Please avoid using exotic dependencies - we do not want to pin the python version,
or common libraries. If your contribution has special needs, consider placing it
in a separate sub-directory with it's own `environment.yml` file.
