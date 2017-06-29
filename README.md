# Quick Start
Run `start_tutorial.sh` to install [BioBlend](http://bioblend.readthedocs.org) in a virtualenv and start the [Jupyter Notebook](http://jupyter.org/).

[Accompanying slides](https://docs.google.com/presentation/d/12wts6oaUH4TLKYMYBzCZPYI3Jf1wzl1ecK0IeCVkJ4s/pub?start=false&loop=false&delayms=3000).
___

# Installation
Go to a directory of you choice and clone this repository:
```bash
$ git clone https://github.com/ratzeni/bioblend-tutorial.git
```
Cd into the tutorial directory
```bash
$ cd bioblend-tutorial
```
Create a new virtual environment in folder `.venv`
```bash
$ virtualenv .venv
```
> [virtualenv](https://virtualenv.pypa.io/en/stable/) is a tool to create isolated Python environments. 
virtualenv creates a folder which contains all the necessary executables to use the packages that a Python project would need.

To begin using the virtual environment, it needs to be activated:
```bash
$ source .venv/bin/activate
```
The name of the current virtual environment will now appear on the left of the prompt to let you know that it’s active. 
From now on, any package that you install using pip will be placed in the my_project folder, isolated from the global Python installation.

Now, install bioblend
```bash
$ pip install bioblend
```
Install [jupyter](http://jupyter.org/)
```bash
$ pip install jupyter
```
Congratulations, you have installed Jupyter Notebook. To run the notebook:
```bash
$ jupyter notebook
```
> The [Jupyter Notebook](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html)
is an open-source web application that allows you to create and share documents that contain live code, equations, 
visualizations and explanatory text. Uses include: data cleaning and transformation, numerical simulation, 
statistical modeling, machine learning and much more.

### Exiting
`Ctrl-c` to exit from notebook.     
When ou are done working in the virtual environment, you can deactivate it:
```bash
$ deactivate
```