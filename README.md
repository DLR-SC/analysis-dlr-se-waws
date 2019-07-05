[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1301033.svg)](https://doi.org/10.5281/zenodo.1301033)

# Analysis of the DLR Knowledge Exchange Workshop Series on Software Engineering
This repository is used to analyze the workshops of the DLR internal workshop series on software
engineering. These workshops are two-day events of the DLR software engineering community and
focus on different main topics every year. The [Juypter notebook](analysis.ipynb) gives an overview
about the basic workshop data and insights into the participant attendance behavior.

The analysis has been performed on Windows 7 using Python 3 and Jupyter notebook.
The analysis code makes use of the libraries [pandas](https://pandas.pydata.org) (BSD 3-Clause License),
[matplotlib](https://matplotlib.org) (Matplotlib License) and [seaborn](https://seaborn.pydata.org/) (BSD 3-Clause License). 

## Using this Jupyter notebook

### Preparation
We used Python 3.7.3 on Windows 7. The dependencies are captured in the [requirements.txt](requirements.txt)
file which we installed in a Python virtual environment as follows:
  - `python -m venv env`
  - `env\Scripts\activate.bat`
  - `pip install -r requirements.txt`

> Currently, there is a bug when activating a virtual environment on Windows operating
> systems using German localization. Please adapt your `env\Scripts\activate.bat` as
> suggested in the [bug report](https://bugs.python.org/issue34144)
> until the problem is fixed.

### Run the Jupyter notebook
- Start Jupyter: `jupyter notebook`
- Your browser should start and you can select the analysis notebook.

## Citation
If you use this work, please cite the specific version using its DOI and the metadata provided in the
[CITATION file](CITATION.cff). For more information on the format, please see [Citation File Format (CFF)](https://citation-file-format.github.io/).

## License
The whole material including data sets and analysis code is licensed under the terms of the
[MIT License](LICENSE).
