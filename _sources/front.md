# Python

## Run on your own computer (Recommended)

You can get the notebooks and run them on your own computer

```shell
git clone https://github.com/cpraveen/python
cd python
jupyter-lab
```

## binder: Read/edit/run the notebooks

Run the code in binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cpraveen/python/HEAD). When you first click on this link, it may take a few minutes to set up the environment with all required packages. Then you can edit and run the notebooks, but you cannot save them; but you can download the notebooks to your computer.

## colab: Read/edit/run the notebooks

You can see a listing of all the notebooks on colab [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cpraveen/python)

or import the individual notebooks into colab using the following links

* [Markdown,Latex](http://colab.research.google.com/github/cpraveen/python/blob/master/00_tips.ipynb)
* [Introduction](http://colab.research.google.com/github/cpraveen/python/blob/master/01_intro.ipynb)
* [Numpy](http://colab.research.google.com/github/cpraveen/python/blob/master/02_numpy.ipynb)
* [Functions](http://colab.research.google.com/github/cpraveen/python/blob/master/03_functions.ipynb)
* [Matplotlib](http://colab.research.google.com/github/cpraveen/python/blob/master/04_matplotlib.ipynb)
* [Sympy](http://colab.research.google.com/github/cpraveen/python/blob/master/05_sympy.ipynb)
* [Scipy](http://colab.research.google.com/github/cpraveen/python/blob/master/06_scipy.ipynb)

After importing into colab, you can edit and run the notebooks but the **changes you make will not be saved**. To save your changes, you must first make a copy of the notebook into your google drive by `File --> Save a copy in drive`.

## Installing python

To install Python on windows, see [Python on Windows](https://learn.microsoft.com/en-us/windows/python/beginners). After you install Python, open PowerShell and install other modules using pip

```shell
pip install numpy scipy sympy matplotlib jupyterlab
```

A better option on windows is to first install [wsl](https://learn.microsoft.com/en-us/windows/wsl/install) and then install python inside wsl.

On mac, I recommend using [homebrew](https://www.brew.sh) and then

```shell
brew install miniforge
conda update conda
conda update --all
conda install numpy scipy sympy matplotlib jupyterlab
```

On Linux also, you can first install [miniforge](https://github.com/conda-forge/miniforge/releases) and then the other modules as above.

## Other resources

* [Python tutorial](https://docs.python.org/tutorial)
* [NumPy Illustrated](http://medium.com/better-programming/numpy-illustrated-the-visual-guide-to-numpy-3b1d4976de1d)
* [Scipy Lecture Notes](http://scipy-lectures.org)
* [OOP in Python for Mathematicians](https://object-oriented-python.github.io)
* Markdown syntax
  * [The Ultimate Markdown Guide](https://medium.com/analytics-vidhya/the-ultimate-markdown-guide-for-jupyter-notebook-d5e5abf728fd)
  * [Working with markdown cells](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html)

## Table of contents

```{tableofcontents}
```
