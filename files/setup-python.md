### Python and Jupyter Notebooks

* [Python](http://python.org) is a popular language for
scientific computing, and great for general-purpose programming as
well. For this workshop we use Python version 3.x. 
Installing all of its scientific packages individually can be
a bit difficult, so we recommend an all-in-one installer.
We will use Anaconda or Miniconda.
They both use [Conda](https://conda.io/en/latest/), the main difference is
that Anaconda comes with a lot of packages pre-installed.
With Miniconda you will need to install the required packages.
We recommend using the Anaconda installation instructions. 

> ## Anaconda installation
> 
> Download and install [Anaconda](https://www.anaconda.com/distribution/#download-section).
> Remember to choose the installer for Python 3.x.
> Anaconda does not include the plotting package plotnine.  To install this package, open your terminal application and
> type:
> 
> ~~~
> conda install -c conda-forge plotnine
> ~~~
> {: .language-bash}
{: .solution}

> ## Miniconda installation
> 
> Miniconda is a "light" version of Anaconda. If you install and use Miniconda
> you will also need to install the workshop packages.
> 
> Download and install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
> following the instructions. Remember to choose the installer for
> Python 3.x.
> 
> From your terminal application, type: 
> ~~~
> conda list
> ~~~
> {: .language-bash}
> 
> To install the packages we'll be using in the workshop, type:
> ~~~
> conda install -y numpy pandas matplotlib jupyter
> conda install -c conda-forge plotnine
> ~~~
> {: .language-bash}
{: .solution}

After installing either Anaconda or Miniconda and the workshop packages,
launch a Jupyter notebook by typing this command from the terminal:

~~~
jupyter notebook
~~~
{: .language-bash}

The notebook should open automatically in your browser. If it does not or you
wish to use a different browser, open this link: <http://localhost:8888>.

For a brief introduction to Jupyter Notebooks, please consult our
[Introduction to Jupyter Notebooks](https://datacarpentry.org/python-ecology-lesson/jupyter_notebooks/) page.

