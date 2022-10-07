[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/luchem/notebooks/HEAD)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

# Open Archive of Educational Chemistry Notebooks

An open collection of educational Jupyter Notebooks relevant to chemistry.
The notebooks can e.g. exemplify how to use a theory, process experimental data, or
visualise data. It can also be tutorials, labs, etc.

## Getting started

We recommend to install
[Anaconda](https://www.anaconda.com/) or the much smaller
[miniconda](https://docs.conda.io/en/latest/miniconda.html).
For the latter, the following installs all dependencies and starts
[JupyterLab](https://jupyter.org) in a web-browser:
~~~ bash
conda env create -f environment.yml # done only once
source activate luchem
jupyter-lab
~~~

## Contributing

Contributions are very welcome and done in the following steps:

1. Make a fork/branch of this repository
2. Add files and update the `README.md` file in the chosen sub-directory
3. Submit a pull-request (PR)
4. Await review

### Dependencies

Please avoid using exotic dependencies - we do not want to pin the python version,
or common libraries. If your contribution has special needs, consider placing it
in a separate directory with it's own `environment.yml` file.
