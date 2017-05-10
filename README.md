## Overview

This is the central repo for all code used in the _House Prices: Advanced Regression Techniques_ 
kaggle competition. Details for this competion can be found here:
https://www.kaggle.com/c/house-prices-advanced-regression-techniques


## Getting started

### Clone the repo

To clone this repo from stash onto your machine, go to your terminal, navigate to the directory
 where you want the code to live, and execute

```bash
git clone https://github.com/DynamitDataScience/kaggle-housing-prices.git
```

### A simple example

To see a simple example of using jupyter notebooks to train machine learning algorithms run the 
`simpleExample.ipynb` file in `source/jupyter`. If you have jupyter (See the _Setting up your development
environment_ section), simply execute

```bash
jupyter notebook path/to/simpleExample.ipynb
```

### Getting the data

The dataset for this kaggle competition is not very large. For convenience, all of
the data has been included in this repo in the data/ directory:

* data/train.csv -- the data used to train and validate the model
* data/test.csv -- the data used to generate submissions
* data/sample_submission.csv -- a sample submission
* data/data_description.txt -- A description of all of the data variables

The data can also be found here: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data.


### Setting up your development environment

These high-level instructions show you how to set up your machine for development using the
python programming language and the popular machine-learning library `scikit-learn`. You are of
course free to use other frameworks. If you have questions about setting up other tools
do not hesitate to ask one of the data science team members.

#### Setup anaconda

Anaconda is a python data science package management tool. It provides everything you need to get
started right out of the box. To install, download the graphical installer appropriate for your 
machine here: https://www.continuum.io/downloads. We recommend choosing the Python 2.7 install version,
so that we can collaborate more easily. Once downloaded, execute the installer and follow the instructions.

#### Installing packages

Anaconda ships with a ton of packages already installed (full list here: https://docs.continuum.io/anaconda/pkg-docs).
Notably, the installer includes `scikit-learn`, `pandas`, and `numpy`. To install a package not included in the anaconda
distribution, open a terminal and execute one of

```bash
conda install [package-name]
```

or

```bash
pip install [package-name] --user
```

Warning: it is not advisable to run `pip` as root as the installed packages can
interfere with your system libraries.

### Jupyter Notebooks

Jupyter Notebooks are a great way to share ideas and code.
Here's a cool notebook using `scikit-learn` implementing a common machine learning classification
algorithm called the Support Vector Machine (SVM):
https://github.com/donnemartin/data-science-ipython-notebooks/blob/master/scikit-learn/scikit-learn-svm.ipynb.




## Contribution guidelines



## Getting help


