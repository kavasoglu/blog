---
layout: post
categories:
  - data science
permalink: /data_science/how_to_start/
order: 1
---
You can easily forget theoretical knowledge if you don't play with them by getting your hands dirty on real projects. To do this, you need to prepare your working environment with installing required packages first.

- Install python
- Install anaconda
- Install jupyter

## Install python

There is always a mystery which version to install with python. This is mainly because of not protecting backward compatibility with the 3rd version and, due to this fact most of legacy applications still prefer to use python 2.7. Since python 3 is the new version and we are not maintaining a legacy application, I recommend you to install probably the latest version of python to play with. Also, 2.7 is being retired and jupyter is switching to version 3 only.  

To install python, follow [https://www.python.org/downloads/](https://www.python.org/downloads/)

## Install anaconda

Anaconda is the open source data science platform to manage environments and packages. It comes with python, `conda` and pre-installed data science packages. The power of anaconda actually comes from conda which is a package and environment manager related to the data science space. Anaconda is a fairly large download so, there is an alternative distribution just comes with conda and python which is called `miniconda`. If you prefer to use miniconda, you need to use conda to install packages.

Package installer for python is called `pip`. Conda is a bit different than pip having the feature of being able to install any software stack packages, so you can install non-python packages as well. Be aware of the fact that not all python libraries are available from conda, and you need to use pip alongside conda to install required packages.

Sample conda usage:
```    
conda install package_name
conda install numpy scipy pandas
conda install numpy=1.10
conda remove package_name
conda update package_name
conda update --all => to update all packages in an environment
conda list => to list installed packages
conda search *beautifulsoup*  or conda search '*beautifulsoup*'
```
To install anaconda: [https://www.anaconda.com/download/](https://www.anaconda.com/download/)

## Install jupyter

`Jupyter` is a web application to serve notebooks (JSON files with the .ipynb extension). A notebook is an essential tool to work with data consisting of code and markdown cells. It can be used at any step of a data project like data cleaning, analyzing, exploration, visualization and machine learning. And, because it is a sharable document and automatically rendered on github, it is easy to work on it together with different people.  

Jupyter comes with anaconda by default, to install it through conda run `conda install jupyter notebook` or through pip run `pip install jupyter notebook`.  

To run jupyter notebooks: `jupyter notebook` (preferably in the directory that you have your notebook to work on).  

Notebooks can be converted to different formats like HTML, Markdown and slideshows. `nbconvert` comes with Jupyter by default, simply run: `jupyter nbconvert --to html notebook.ipynb`

Useful shortcuts when working with a notebook:
- `ctrl + enter` => execute a cell
- `esc + a` => insert a cell above
- `esc + b` => insert a new cell below
- `esc + m` => convert a cell to a markdown cell
- `esc + c` => convert a cell to a code cell
- `esc + l` => put / remove line numbers
- `esc + dd` => delete cell

Check out [http://nbviewer.jupyter.org/](http://nbviewer.jupyter.org/) to render your notebooks from any location.
