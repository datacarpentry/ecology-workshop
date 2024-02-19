---
title: Setup for Python workshops
---






### Python and Jupyter Notebooks

- [Python](https://python.org) is a popular language for
  scientific computing, and great for general-purpose programming as
  well. For this workshop we use Python version 3.x.
  Installing all of its scientific packages individually can be
  a bit difficult, so we recommend an all-in-one installer.
  We will use Anaconda or Miniconda.
  They both use [Conda](https://conda.io/en/latest/), the main difference is
  that Anaconda comes with a lot of packages pre-installed.
  With Miniconda you will need to install the required packages.
  We recommend using the Anaconda installation instructions.

:::::::::::::::: spoiler

## Anaconda installation

Download and install [Anaconda](https://www.anaconda.com/download).
Remember to choose the installer for Python 3.x.
Anaconda does not include the plotting package plotnine.  To install this package, open your terminal application and
type:

```bash
conda install -c conda-forge plotnine
```

:::::::::::::::::::::::::

:::::::::::::::: spoiler

## Miniconda installation

Miniconda is a "light" version of Anaconda. If you install and use Miniconda
you will also need to install the workshop packages.

Download and install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
following the instructions. Remember to choose the installer for
Python 3.x.

From your terminal application, type:

```bash
conda list
```

To install the packages we'll be using in the workshop, type:

```bash
conda install -y numpy pandas matplotlib jupyter
conda install -c conda-forge plotnine
```

:::::::::::::::::::::::::

After installing either Anaconda or Miniconda and the workshop packages,
launch a Jupyter notebook by typing this command from the terminal:

```bash
jupyter notebook
```

The notebook should open automatically in your browser. If it does not or you
wish to use a different browser, open this link: [http://localhost:8888](https://localhost:8888).

For a brief introduction to Jupyter Notebooks, please consult our
[Introduction to Jupyter Notebooks](https://datacarpentry.org/python-ecology-lesson/jupyter_notebooks/) page.



## Software

| Software            | Install                         | Manual | Available for         | Description                                               | 
| ------------------- | ------------------------------- | ------ | --------------------- | --------------------------------------------------------- |
| Spreadsheet program | [Link](https://www.libreoffice.org/download/download/)                                | [Link](https://documentation.libreoffice.org/en/english-documentation/)       | Linux, MacOS, Windows | Spreadsheet program for organizing tabular data.          | 
| OpenRefine          | [Link](http://openrefine.org/download.html)                                | [Link](http://openrefine.org/documentation.html)       | Linux, MacOS, Windows | Program for reproducibly cleaning data.                   | 
| Python              | See install instructions below. |        | Linux, MacOS, Windows | Programming language for data analysis and visualisation. | 
| SQLite Browser      | [Link](http://sqlitebrowser.org/dl/)                                | [Link](https://github.com/sqlitebrowser/sqlitebrowser/wiki)       | Linux, MacOS, Windows | Tool for creating, designing, and editing database files. | 






## SQL

- SQL is a specialized programming language used with databases.  We
  use a simple database manager called [SQLite](https://www.sqlite.org/)
  in our lessons. We will use the [DB Browser for SQLite](https://sqlitebrowser.org/) program,
  which is available for all major platforms.

- To install the DB Browser, go to their [download page](https://sqlitebrowser.org/dl/) and choose the correct installer for
  your operating system. Once the installer is downloaded, double click on it (you may need to open your Downloads folder), follow
  any other instructions that appear, and
  DB Browser should install. After installing, you can delete the installer `.dmg` file.








## Data

You can download all of the data used in this workshop by clicking
[this download link](https://ndownloader.figshare.com/articles/1314459/versions/9). The file is 38.4 MB.

Clicking the download link will automatically download all of the files to your default download directory as a single compressed
(`.zip`) file. To expand this file, double click the folder icon in your file navigator application (for Macs, this is the Finder
application).

For a full description of the data used in this workshop see the [data page](learners/data.md).








### Spreadsheet program

- To interact with spreadsheets, we can use LibreOffice, Microsoft Excel, Gnumeric, OpenOffice.org, or other programs.
  Commands may differ a bit between programs, but the general ideas for thinking about spreadsheets are the same. For this workshop,
  we recommend using either Microsoft Excel (paid software) or LibreOffice (free and open source). Other spreadsheet programs may
  not have all of the features we will be exploring in this workshop.

- To install LibreOffice, go to their [download page](https://www.libreoffice.org/download/download/). The website should
  automatically select the correct option for your operating system. Click the "Download" button. You will go to a page that asks about a
  donation, but you don't need to make one. Your download should begin automatically. Once the installer is downloaded, double click on it (you may need to open your Downloads folder) and LibreOffice should install.








### OpenRefine

- OpenRefine is a Java program that runs on your local machine (not on the cloud). Although it displays in your browser, no web
  connection is needed and your data remains local. You need to have a ‘Java Runtime Environment' (JRE) installed on your computer to run
  OpenRefine. If you don't already have one installed and are running Windows, then you can download the "Windows kit with embedded Java" version from the downloads page. You can also download and install Java from [https://java.com](https://java.com) by going to the site and clicking "Free Java Download".

- To install OpenRefine, go to their [download page](https://openrefine.org/download.html). From the download page, select either "Windows
  kit", "Mac kit", or "Linux kit" - depending on your operating system - and follow the instructions next to your download link. This
  lesson has been tested with the recent versions of OpenRefine, at least 3.4.1. **If you are using an older version, it is
  recommended you upgrade to the latest tested version.**

- You may get an error message: "OpenRefine.app can't be opened because it is from an unidentified developer." If you get this message,
  open your system preferences and click "Security \& Privacy". You will see a message "OpenRefine.app was blocked from opening because it
  is from an unidentified developer." Click "Open Anyway" and "Yes". OpenRefine should open in your default web browser.

- OpenRefine does not support Internet Explorer or Edge. Please use Firefox, Chrome or Safari instead.



Congratulations! You are now ready for the workshop!


