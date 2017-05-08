## Overview

This is the central repo for all code used in the _Ranking Expedia Search Results_ 
kaggle competition. Details for this competion can be found here:
https://www.kaggle.com/c/expedia-personalized-sort.


## Getting started

### Clone the repo

To clone this repo from stash onto your machine, go to your terminal and execute 
(assuming that your stash username is "jane.doe")
```$bash
git clone http://jane.doe@stash.dynamit.com/scm/dt/ranking-expedia-search-results.git
```

Stash also has a nice graphical repo management tool called 
Source Tree (available here: https://www.sourcetreeapp.com/)
if you prefer that.

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
```$bash
conda install [package-name]
```
or
```$bash
pip install [package-name] --user
```
Warning: it is not advisable to run `pip` as root as the installed packages can
interfere with your system libraries.






## Motivation

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Installation

Provide code examples and explanations of how to get the project.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)