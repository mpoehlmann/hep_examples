# High Energy Physics Examples

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mpoehlmann/hep_examples/master?urlpath=lab)

High energy physics examples and tutorials.


## Overview
I'm a PhD student studying experimental high energy physics (HEP) with a focus on rare event detection.
In my free time, I have compiled examples of analysis macros, code snippets, and other coding knowledge which I think are useful.
My goal is to help HEP students who have some coding experience to quickly gain proficiency in writing HEP analysis code.
Feel free to let me know if you discover any bugs or have requests for specific examples.

This tutorial is divided into the following chapters:

1. Introduction
    1. Getting started with ``bash`` and ``jupyter``
    1. Setting up computing environment
1. Basic ``C/C++``, ``Python``, and ``Julia``
1. Advanced Python
    1. Speed up code with ``numba``
    1. HEP analysis with ``uproot`` and ``awkward-array`` packages
1. Advanced C/C++
1. Advanced Julia
1. ROOT
1. Plotting Library
1. Machine Learning
    1. Applications of machine learning in HEP
1. Geant4

## Examples
The ``examples`` folder contains runable analysis macros.

## Tutorials
The ``tutorials`` folder contains step-by-step instructions for items I wanted to include but didn't want to put in the chapter ``jupyter`` notebooks.


## Repository notes 
This repository uses Python, Julia, and ROOT environments side-by-side.
The ``environment.yml`` file handles the installation of an anaconda python environment, including the required Python packages. It also installs ROOT
The ``REQUIRE`` file specifies the Julia packa
The former corresponds , and the latter corresponds to a Julia environment. 
Both kernels will be available to you in a built Binder environment.

## TODO
- **notebooks**
  - ch 1
    - installation
    - jupyter
  - ch 2
    - debugging
  - ch 3
    - example pstats file
- **examples**
  - 
- **tutorials**
  - sublime.md
- **cheatsheets**
  - conda
  - sublime
  - 