# Description

This repository contains some data science Jupyter notebooks that are submitted to [Kaggle](https://www.kaggle.com/davytoch) in order to build up my competences in data science related fields like statistics and machine learning.

# Prerequisites

If you want to run the Jupyter notebooks locally, you need: 

- [Python 3.12 or higher](https://www.python.org/) installed.
- [Miniconda or similar](https://docs.anaconda.com/miniconda) installed. You then need a local Conda environment **kaggle-python-notebook** configured with following shell commands:

```
conda create \
  --name kaggle-python-notebook \
  python=3.12 ipython
```

and then install following packages:

```
%pip install -U -q scikit-learn
%pip install -U -q pandas
%pip install -U -q numpy
%pip install -U -q matplotlib
```
