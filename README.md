# Code Recipes

[Original repository on GitHub](https://github.com/Hvass-Labs/Code-Recipes)

Original author is [Magnus Erik Hvass Pedersen](http://www.hvass-labs.org)


## Introduction

This is a collection of source-code recipes for solving small problems that
I could not find solutions for on the internet. These are implemented in
Python unless otherwise noted.


## Recipes

- **Resample KDE** ([Notebook](https://github.com/Hvass-Labs/Code-Recipes/blob/master/Resample-KDE.ipynb)) ([Google Colab](https://colab.research.google.com/github/Hvass-Labs/Code-Recipes/blob/master/Resample-KDE.ipynb)) </br> Resample a Probability Density Function (PDF) estimator such as the Kernel Density Estimation (KDE) that has been fitted to some data. This is useful if you want to save and load the KDE without saving all the raw data. We also show how to draw random samples from a histogram.


## Run in Google Colab

If you do not want to install anything on your own computer, then the Notebooks
can be viewed, edited and run entirely on the internet by using
[Google Colab](https://colab.research.google.com).

You click the "Google Colab"-link next to the recipes listed above. You can
view the Notebook on Colab but in order to run it you need to login using your
Google account.

Most of the required Python packages should already be installed on Google
Colab, but there is a `%pip install` command near the top of each Notebook
which will run automatically on Google Colab, so as to install the required
Python packages for that particular Notebook.


## Run on Your Own Computer

If you want to run these recipes on your own computer, then it is
easiest if you download the whole repository from GitHub,
instead of just downloading the individual Python Notebooks.


### Git Clone

The easiest way to download and install it is by using git from the command-line:

    git clone https://github.com/Hvass-Labs/Code-Recipes.git

This creates the directory `Code-Recipes` and downloads all the files to it.

This also makes it easy to update the files, simply by executing this
command inside that directory:

    git pull


### Zip-File

You can also [download](https://github.com/Hvass-Labs/Code-Recipes/archive/refs/heads/main.zip)
the contents of the GitHub repository as a Zip-file and extract it manually.


### Installation

If you want to run these tutorials on your own computer, then it is best
to use a virtual environment when installing the required packages,
so you can easily delete the environment again. You can use [Anaconda](https://www.anaconda.com/download) for this:

    conda create --name code-recipes python=3

Then you switch to the virtual environment and install the required packages.

    conda activate code-recipes
    pip install -r requirements.txt

When you are done working on the project you can deactivate the virtualenv:

    conda deactivate


### Run 

Once you have installed the required Python packages in a virtual environment,
you run the following command from the `Code-Recipes` directory to view,
edit and run the Notebooks:

    conda activate code-recipes
    jupyter notebook


## License (MIT)

This is published under the
[MIT License](https://github.com/Hvass-Labs/Code-Recipes/blob/master/LICENSE)
which allows very broad use for both academic and commercial purposes.

You are very welcome to modify and use this source-code in your own project.
Please keep a link to the [original repository](https://github.com/Hvass-Labs/Code-Recipes).
