# Self-organized criticality on networks

This repository contains a project developed for the Models and Numerical Methods in Physics course (Master Degree in Physics, University of Bologna). It is a simulation and analysis of the Bak-Tang-Wiesenfeld sandpile model on different complex network topologies.

## How to use this repository

The project is written in the form of a Jupyter notebook, and can be read and executed in the [`project_notebook.ipynb`](https://github.com/riccardo03-maker/SOC_on_networks/blob/main/project_notebook.ipynb). However, the simulation is implemented using the Python package [`SandNet`](https://github.com/riccardo03-maker/SandNet), which needs to be correctly installed. The instructions for the correct installation of the package and execution of the notebook are described in the [Installation](#Installation) section.

Alternatively, it is possible to directly read the notebook already executed in the [`project_notebook.html`](https://github.com/riccardo03-maker/SOC_on_networks/blob/main/project_notebook.html) file.

All the plots drawn using the code written in the notebook are stored in the [`plots`](https://github.com/riccardo03-maker/SOC_on_networks/tree/main/plots) folder.

## Installation

First clone this repository to your local working directory

```bash
git clone https://github.com/riccardo03-maker/SOC_on_networks
```
and move to the project root directory.

```bash
cd SOC_on_networks
```
Then do the same for the GitHub repository of the `SandNet` package

```bash
git clone https://github.com/riccardo03-maker/SandNet
cd SandNet
```
The installation of the `SandNet` package can now be done by using pip

```bash
python -m pip install .
cd ../
```
or, for development mode

```bash
python -m pip install --editable . --user
cd ../
```
Remember that the minimum Python version required for the `SandNet` package is Python 3.9.

Now you can correctly execute the simulation and analysis implemented in the [`project_notebook.ipynb`](https://github.com/riccardo03-maker/SOC_on_networks/blob/main/project_notebook.ipynb) using the `SandNet` package. All the other Python packages needed for the analysis have been already installed into your local Python version during the installation of `SandNet`.

## Authors

*  **Riccardo Grandicelli**
