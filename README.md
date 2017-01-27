# Pandas Tutorial

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/alessandrochecco/pandas-tutorial)

This repository contains the material (notebooks, data) for the pandas tutorial. Tutorial derived from Joris Van den Bossche: [releases page](https://github.com/jorisvandenbossche/pandas-tutorial/releases).

## Requirements to run this tutorial

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

Once this is installed, the following command will install all required packages in your Python environment:
```
conda install pandas jupyter seaborn
```

But of course, using another distribution (e.g. Enthought Canopy) or pip is good as well, as long
as you have the above packages installed.


## Downloading the tutorial materials

If you have git installed, you can get the material in this tutorial by cloning this repo:

    git clone https://github.com/jorisvandenbossche/pandas-tutorial.git

As an alternative, you can download it as a zip file:
https://github.com/jorisvandenbossche/pandas-tutorial/archive/master.zip.
I will probably make some changes until the start of the tutorial, so best to download
the latest version then (or do a `git pull` if you are using git).

Two data files are not included in the repo, you can download them from: [`titles.csv`](https://drive.google.com/open?id=0B3G70MlBnCgKajNMa1pfSzN6Q3M) and [`cast.csv`](https://drive.google.com/open?id=0B3G70MlBnCgKal9UYTJSR2ZhSW8) and put them in the `/data` folder.

## Content

To view the content on nbviewer:

- [01 - Basics](https://github.com/AlessandroChecco/pandas-tutorial/blob/master/Pandas%20tutorial%20-%20part%201.ipynb)
- [02 - Indexing and Groupby](https://github.com/AlessandroChecco/pandas-tutorial/blob/master/Pandas%20tutorial%20-%20part%202.ipynb)
- [03 - Time series](https://github.com/AlessandroChecco/pandas-tutorial/blob/master/Pandas%20tutorial%20-%20part%203.ipynb)
