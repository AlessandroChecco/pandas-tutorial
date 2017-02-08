# Pandas Tutorial - [goo.gl/BPYJhp](http://goo.gl/BPYJhp)

This repository contains the material (notebooks, data) for the pandas tutorial. Tutorial derived from Joris Van den Bossche: [releases page](https://github.com/jorisvandenbossche/pandas-tutorial/releases).

## Requirements to run this tutorial

If you have a laptop, I would suggest to go to section 2 and install the software on your laptop, otherwise from the computer in the classroom please follow section 1.

### 1. From the lab computer (It requires a student account)

1. Log in with your account.
2. Download and extract this file https://github.com/AlessandroChecco/pandas-tutorial/archive/master.zip.
3. Copy the just extracted folder "pandas-tutorial" in drive U:
4. From the start menu execute Jupyter Notebook

### 2. From your laptop

1. Install [conda](http://conda.pydata.org/docs/intro.html) environment manager to install all the requirements 
(you can install [miniconda](http://conda.pydata.org/miniconda.html) or install the (very large) Anaconda software
distribution, found at http://continuum.io/downloads).
2. The following command will install all required packages in your Python environment:
`conda install pandas jupyter seaborn`
3. Git clone this repository, or alternatively download and extract this file https://github.com/AlessandroChecco/pandas-tutorial/archive/master.zip.

#### 2b. Other environments

If you want to use other environment: you will need to install [jupyter](http://jupyter.readthedocs.io/en/latest/install.html).
To follow this tutorial you need to have the following packages installed:

- Python version 2.6-2.7 or 3.3-3.5
- `pandas` version 0.18.0 or later: http://pandas.pydata.org/ (previous versions will work for most examples as well)
- `numpy` version 1.7 or later: http://www.numpy.org/
- `matplotlib` version 1.3 or later: http://matplotlib.org/
- `ipython` version 3.x with notebook support, or `ipython 4.x` combined with `jupyter`: http://ipython.org
- `seaborn` (this is used for some plotting, but not necessary to follow the tutorial): http://stanford.edu/~mwaskom/software/seaborn/

#### 2c. Alternative method (zero requirements! But it might be down...)

Try to click here [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/alessandrochecco/pandas-tutorial)

#### 2d. Alternative method (it requires a google account)

1. Install [CoLaboratory](http://colaboratory.jupyter.org/welcome/) and upload there the main files. It requires google drive.
2. Download and extract this file https://github.com/AlessandroChecco/pandas-tutorial/archive/master.zip.

#### 2e. Alternative method (nothing to install, it needs a student account and eduroam/internal connection)

Try [JupyterHub](https://jupyter.shef.ac.uk) and upload there the alternative version of the notebooks:

1. New/Terminal
2. Execute `wget https://github.com/AlessandroChecco/pandas-tutorial/archive/master.zip`
3. Execute `unzip master.zip`
4. Close the tab
5. Click on pandas-tutorial folder and launch JupyterHub notebooks (ipynb files marked with jupyterhub name).

## Content (no interaction)


If nothing else works you can still look at the documents. To view the content on nbviewer:

1. [Introduction](https://github.com/AlessandroChecco/pandas-tutorial/blob/master/Introduction.ipynb)
2. [Basics](https://github.com/AlessandroChecco/pandas-tutorial/blob/master/Pandas%20tutorial%20-%20part%201%20(solved).ipynb)
3. [Indexing and Groupby](https://github.com/AlessandroChecco/pandas-tutorial/blob/master/Pandas%20tutorial%20-%20part%202.ipynb)
4. [Time series](https://github.com/AlessandroChecco/pandas-tutorial/blob/master/Pandas%20tutorial%20-%20part%203.ipynb)
