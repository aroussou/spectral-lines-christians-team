***********
SNFcocktail
***********

Nuclear theory and predictive power
===========================================================
:Author: Christian Forssen (christian.forssen@chalmers.se)

This repository contains lectures and accompanying material presented
by Christian Forssen (Chalmers, Sweden) at the 2018 Euroschool on
Exotic Beams, Leuven, Belgium.

Interested students are encouraged to install python and the required
modules to test themselves the examples that were discussed at the lectures.

Installation
------------

Download the repo from github::

    git clone https://github.com/cforssen/Euroschool2018_Forssen.git

The scripts depend on several scientific modules (see
the list in environment.yml) and require a python3.5 installation. 

Dependencies are best installed using ``conda`` by creating
a virtual environment:

    conda env create
    source activate euroschool-env

 Note that we employ a rather broad list of packages in this notebook.
 After all, we explore several different application areas. The core
 packages are numpy and matplotlib, while the others are used for the
 various examples. It could happen that some packages are not included
 in the conda default channel and that the above installation
 fails. This should be solved by adding the
 [conda-forge](https://conda-forge.org/) channel: 

    conda config --add channels conda-forge

To deactivate virtual environment::

    source deactivate


Code overview
-------------

``Forssen_lecture1.ipynb`` ......... Lecture 1 on "Precitive theories and Bayesian statistics" as a jupyter ipython notebook

``Forssen_lecture2.ipynb`` ......... Lecture 2 on "Ab initio nuclear theory" as a jupyter ipython notebook

``environment.yml`` ... Package dependencies

``LICENCE.txt`` .............. MIT License

``README.rst`` .......... This.


Support
-------

For questions regarding this software, feel free to e-mail the main author.

