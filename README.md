[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rmadar/lecture-python/master)

# Introduction to Python for Data Analysis

This repository contains the material for lecture of a [data scientist university degree](https://www.uca.fr/formation/nos-formations/catalogue-des-formations/du-data-scientist-23438.kjsp) proposed at Université Clermont-Auvergne (UCA), which is mostly based on a [NumPy tutorial](https://github.com/MLatCezeaux/intro_numpy) that I gave at the [Laboratoire de Physique de Clermont](http://clrwww.in2p3.fr/) in April 2019. No prerequisite knowledge is assumed but being familiar with one progamming language might be useful. However, it is better to know about some basic mathemtatics like simple vectorial operation or statistics.


## General scope of the lecture

The main goal of this lecture is to make people familiar with python and data analysis tools in order to make them able to extend their knowledge on *themself*. Pratical exercises and small projects are also proposed to provide a few working examples of data manipulations with different level of complexity. The full lecture material is available in PDF [here](https://github.com/rmadar/lecture-python/raw/master/documentation/PythonIntroductionDU.pdf).

**What this lecture is?** A *basic* and *practical* introduction to python together with some of the most important data analysis tools namely `numpy`, `matplotlib` and `pandas`.

**What this lecture isn't?** Neither a formal introduction to python, nor a extensive demonstration of all features available in the tools mentioned above.


## Content of the lecture

There are a lot of information in this lecture. In order to help you to focus on important aspect, each chapter start with a list of expected skills that you should take away, ranked with three levels: *basic*, *medium*, *expert*.

**1. Practical Introduction to Python.** This first section is dedicated to basic object type and operation in python. Fonctions will also be described but object oriented programming will not be covered -- *[online notebook](https://nbviewer.jupyter.org/github/rmadar/lecture-python/blob/master/lectures/1-PythonIntroduction.ipynb)*

**2. Introduction to numpy**. Differences between usual python objects and numpy objects will be introduced -- *[online notebook](https://nbviewer.jupyter.org/github/rmadar/lecture-python/blob/master/lectures/2-NumpyIntroduction.ipynb)*

**3. Three tools to know.** This section gives a glimpse of `matplotlib`, `pandas` and `scipy` packages allowing powerful data analysis -- *[online notebook](https://nbviewer.jupyter.org/github/rmadar/lecture-python/blob/master/lectures/3-ToolsToKnow.ipynb)*

**4. Multidimensional data manipulation.** Non-trivial operation for multidimensional data using the full power of numpy. Most of these operation can be performed with existing tools but it is intructive to do it once with native numpy -- *[online notebook](https://nbviewer.jupyter.org/github/rmadar/lecture-python/blob/master/lectures/4-HighDimensionalData.ipynb)*

**5. Introduction to image processing.** Very first steps of image processing (definition, plotting, operation) including basic filters application (noising, sharpen, border detection) -- [*online notebook*](https://nbviewer.jupyter.org/github/rmadar/lecture-python/blob/master/lectures/5-ImageProcessing.ipynb)


**Other practical examples.** Depending on the remaining time (and the people taste), we can go through different topics among the following ones. Some of them can be also used as a project performed by students.
   + Fourier analysis
   + Principal component analysis (PCA)
   + Random Forest regression
   + Gaussian processes


## How to get prepared

**1. Get familiar with python.** I would recommand two links: [w3school tutorial](https://www.w3schools.com/python/) (both basic and complete) and [https://www.learnpython.org](https://www.learnpython.org) (code can be ran directly within your web browser).

**2. Install python with anaconda.** In order to run python on your own machine, you should install it. I would recommand [anaconda](https://www.anaconda.com/) for this, which also includes jupyter-notebook.

**3. Install git.** This is a versioning software which can be installed following these [instructions](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). This whole repository can be *cloned* using `git clone https://github.com/rmadar/lecture-python` command.

**4. Get familiar with notebooks.** This represents a nice environement combining codes, notes and plots. This is very powerful to learn something and play with it. You can checkout [this video](https://www.youtube.com/watch?v=CwFq3YDU6_Y) or [this post](https://realpython.com/jupyter-notebook-introduction/).

## Prerequisites to run notebooks

+ Python 3
+ matplotlib
+ NumPy
+ pandas
+ SciPy
+ Pillow

or use the full list of dependencies to build a working conda environment with the `environment.yml`
