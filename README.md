# Git Tutorial

This project is an introduction to the git version control system for CGI's Chattanooga office November 2017 Lunch and Learn series. 

## Installation

This project requires [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed.

The tutorial uses a [Jupyter Notebook](http://jupyter.org/) with [bash_kernel](https://pypi.python.org/pypi/bash_kernel) installed.  The easiest way to install the project dependancies is to download and install [Anaconda](https://www.anaconda.com/download/)
and, from a bash shell, run

```
git clone git@github.com:grantcooksey/Lunch-And-Learn-Git-Into.git
```
to clone the repository to your local computer. To create your environment and install dependancies, run

```
conda env create -f environment.yml
```
Finally, from the project root directory, start up the notebook with
 
```
jupyter notebook
```
and navigate to the tutorial to start the notebook.