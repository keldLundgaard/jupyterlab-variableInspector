# jupyterlab_variableinspector



Jupyterlab extension that shows currently used variables and their values. The goal is to provide a tool similar to the variable inspector in RStudio.

This project is based on the [variable inspector extension for jupyter notebooks](https://github.com/ipython-contrib/jupyter_contrib_nbextensions/tree/master/src/jupyter_contrib_nbextensions/nbextensions/varInspector) from where the `var_list.py`function is used. The architecture is heavly inspired by the [inpector extension included in juypterlab](https://github.com/jupyterlab/jupyterlab/tree/master/packages/inspector-extension).

For the time being, this project is still in its first steps. Contributions in any form are very welcome!

## Features
![Demogif](early_demo.gif)
- Allows inspection of variables for both python consoles and python notebooks


## Prerequisites

* JupyterLab

## Installation
In this early stage you can install this extension by building it from source.

Download the repository and build the project with `npm install` and `npm run build` and use `jupyter labextension install . ` in the project's root directory.


## TODOs
~~- [ ] Load inspection script from relative paths.~~
- [ ] Add a better presentation (datagrids) for dataframes and ndarrays.
- [ ] Allow sorting the inspector table.
- [ ] Add support for other languages.



