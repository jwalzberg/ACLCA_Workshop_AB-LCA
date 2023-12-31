# <center> An Introduction to Agent-Based Life Cycle Assessment with Python </center>

This is an introduction to agent-based life cycle assessment (AB-LCA). This notebook will cover the basics of agent-based modeling (ABM) with Mesa, a Python library dedicated to facilitate the building of agent-based models. Then it will present a simple AB-LCA model on plastic recycling that leverages both Mesa and Brightway2, an open source Python framework for LCA.

At the end of this notebook, you will be able to:

* *Understand the Mesa's basic building blocks.*
* *Build a simple ABM.*
* *Link the ABM outputs to an LCA and vice versa.*

This introduction is written in an Jupyter notebook, an online scientific notebook which combines, text, data, images, and programming. It is built upon both Mesa and Brightway2 tutorials.

* [Mesa tutorial](https://mesa.readthedocs.io/en/stable/tutorials/intro_tutorial.html).
* [Brightway2 tutorial](https://github.com/brightway-lca/brightway2/blob/master/notebooks/Getting%20Started%20with%20Brightway2.ipynb).

You should **download the notebook** in this repository and follow along!

## Getting started

First you need to install the following libraries in your base or a new Python or Conda environment (see [Managing conda environment](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)):

* mesa==0.8.9
* networkx==3.1
* numpy==1.25.0
* pandas==1.5.3
* brightway2==2.4.3
* matplotlib==3.7.1
* seaborn==0.12.2

Make sure you also have enum, math, and random. An easier solution is to install all the libraries at once [using the AB-LCA.yml file](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) in the [ACLCA_Workshop_AB-LCA repository](https://github.com/jwalzberg/ACLCA_Workshop_AB-LCA).

Then you need to clone the [ACLCA_Workshop_AB-LCA repository](https://github.com/jwalzberg/ACLCA_Workshop_AB-LCA) (see [cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)), start the "ACLCA_Workshop_AB-LCA" notebook, and activate the environment (or stay on the base if you added the libraries to your base environment) by clicking Kernel and "change kernel" in the Jupyter notebook menu (you should see the name of the environment as kernel option).

Alternatively, you can download the repository as a zip file, unzip the content of the zip file in a folder, start Jupyter notebook and navigate to the "ACLCA_Workshop_AB-LCA" notebook. Then, a cell in the Jupyter notebook will enable you to install all the necessary packages. Beware that it may change your current base or Python environment (i.e., the kernel you use to run this Jupyter notebook). If that is an issue, it might be wiser to create a specific environment prior to run the Jupyter notebook.
