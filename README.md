# Pandas Tutorial

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/alessandrochecco/pandas-tutorial)

This repository contains the material (notebooks, data) for the pandas tutorial. Tutorial derived from Joris Van den Bossche: [releases page](https://github.com/jorisvandenbossche/pandas-tutorial/releases).

## Requirements to run this tutorial

### 1. Preferred method (faster but harder to install)

You will need to install [jupyter](http://jupyter.readthedocs.io/en/latest/install.html).
To follow this tutorial you need to have the following packages installed:

- Python version 2.6-2.7 or 3.3-3.5
- `pandas` version 0.18.0 or later: http://pandas.pydata.org/ (previous versions will work for most examples as well)
- `numpy` version 1.7 or later: http://www.numpy.org/
- `matplotlib` version 1.3 or later: http://matplotlib.org/
- `ipython` version 3.x with notebook support, or `ipython 4.x` combined with `jupyter`: http://ipython.org
- `seaborn` (this is used for some plotting, but not necessary to follow the tutorial): http://stanford.edu/~mwaskom/software/seaborn/

I recommend to use the [conda](http://conda.pydata.org/docs/intro.html) environment manager to install all the requirements 
(you can install [miniconda](http://conda.pydata.org/miniconda.html) or install the (very large) Anaconda software
distribution, found at http://continuum.io/downloads).

Once this is installed, the following command will install all required packages in your Python environment (optional):
```
conda install pandas jupyter seaborn
```

But of course, using another distribution (e.g. Enthought Canopy) or pip is good as well, as long
as you have the above packages installed.

### 2. Alternative method (nothing to install, it needs a student account and eduroam/internal connection)

Try [JupyterHub](https://jupyter.shef.ac.uk) and upload there the alternative version of the notebooks:

1. New/Terminal
2. Execute `wget https://github.com/AlessandroChecco/pandas-tutorial/archive/master.zip`
3. Close the tab
4. Click on pandas-tutorial folder and launch JupyterHub notebooks

### 3. Alternative method #2 (it requires a google account)

Install [CoLaboratory](http://colaboratory.jupyter.org/welcome/) and upload there the main files. It requires google drive.

### 4. Alternative method #3 (zero requirements!)

Try to click here [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/alessandrochecco/pandas-tutorial)

## Downloading the tutorial materials (needed for methods 1, 2 and 3)

If you have git installed, you can get the material in this tutorial by cloning this repo:

    git clone https://github.com/AlessandroChecco/pandas-tutorial.git

As an alternative, you can download it as a zip file:
https://github.com/AlessandroChecco/pandas-tutorial/archive/master.zip.
I will probably make some changes until the start of the tutorial, so best to download
the latest version then (or do a `git pull` if you are using git).


## Content (no interaction)

If nothing else works you can still look at the documents. To view the content on nbviewer:

- [01 - Basics](https://github.com/AlessandroChecco/pandas-tutorial/blob/master/Pandas%20tutorial%20-%20part%201.ipynb)
- [02 - Indexing and Groupby](https://github.com/AlessandroChecco/pandas-tutorial/blob/master/Pandas%20tutorial%20-%20part%202.ipynb)
- [03 - Time series](https://github.com/AlessandroChecco/pandas-tutorial/blob/master/Pandas%20tutorial%20-%20part%203.ipynb)
