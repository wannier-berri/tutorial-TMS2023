[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wannier-berri/tutorial-TMS2023/HEAD)

# Tutorial for Topological Matter School - 2023

# Overview

The tutorial will teach how to numericaly evaluate magnetotransport (within semiclassical formalism)  and optical properties. Or any other quantity which can be expressed as a Brillouin zonde integral. We will use the code [WannierBerri](https://wannier-berri.org/). This code was primarily developed for ab-initio calculations of Berry curvatures and similar quantities (see [paper](https://www.nature.com/articles/s41524-021-00498-5) ) 
but now it can be equally used for **k.p** or **tight-binding** models. We will **stick to the models** in the tutorial.  

The tutorials will be provided as [Jupyter](https://jupyter.org/) notebooks  and will de uploaded to this repository 
shortly before the session. So far the students are asked only to prepare their computers 

# Installation

## Briefly: 

Please install Jupyter Notebook, WanierBerri and also pythtb

```
pip install   pythtb notebook matplotlib "wannierberri>=0.14.0"
```
This will also install all dependencies

## In more words:

First, tutrial is using `python3` language. Therefore, please install it on your computer (if not installed yet) 
You may consider the [Anaconda](https://www.anaconda.com/) distribution, but the python which comes with your OS (at least Mac/Linux) whouls be fine. 

We regularly test WannierBerri with pytho versions 3.8, 3.9 and 3.10. 

There may be issues of some package dependencies with python 3.11 on some systems (e.g. see [here](https://github.com/wannier-berri/wannier-berri/actions/runs/5920172822/job/16051132708?pr=266) ). If you have python3.11 and experience such issues, try to create a virtual environment with an older version of python, following [instructions](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands)

```
conda create -n python39 python=3.9
conda activate python39
```

[pythtb](https://www.physics.rutgers.edu/pythtb/index.html) is a package that we will use to construct tight-binding models.

**Make sure you have the fresh version of wannierberri**

# Check you installation

Open the tutorial `tutorials/tutorial_test.ipynb` with Jupyter Notebook. Try to run all the cells in it
If you run all the cells without errors, you are good to go even if you do not understand what is going on.


# If you have problems 

* open an Issue in this repository (you need to login to GitHub for that)
* look through issues in main [repository](https://github.com/wannier-berri/wannier-berri/issues)
* try to find me at the school (I will be around) or some of the following people:


Looking forward to seeing you at the tutorial!

Stepan Tsirkin
