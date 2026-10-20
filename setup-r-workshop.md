---
title: Setup for R workshops
---






### R and RStudio

- R and RStudio are separate downloads and installations. R is the
  underlying statistical computing environment, but using R alone is no
  fun. RStudio is a graphical integrated development environment (IDE) that makes
  using R much easier and more interactive. You need to install R before you
  install RStudio. After installing both programs, you will need to install
  some specific R packages within RStudio. Follow the instructions below for
  your operating system, and then follow the instructions to install
  **`tidyverse`** and **`RSQLite`**.

#### Windows

:::::::::::::::: spoiler

## If you already have R and RStudio installed

- Open RStudio, and click on "Help" > "Check for updates". If a new version is
  available, quit RStudio, and download the latest version for RStudio.

- To check which version of R you are using, start RStudio and the first thing
  that appears in the console indicates the version of R you are
  running. Alternatively, you can type `sessionInfo()`, which will also display
  which version of R you are running. Go on
  the [CRAN website](https://cran.r-project.org/bin/windows/base/) and check
  whether a more recent version is available. If so, please download and install
  it. You can [check here](https://cran.r-project.org/bin/windows/base/rw-FAQ.html#How-do-I-UNinstall-R_003f) for
  more information on how to remove old versions from your system if you wish to do so.

- Follow the steps in the instructions [for everyone](#for-everyone) at the
  bottom of this page.
  

:::::::::::::::::::::::::

:::::::::::::::: spoiler

## If you don't have R and RStudio installed

- Download R from
  the [CRAN website](https://cran.r-project.org/bin/windows/base/release.htm).

- Run the `.exe` file that was just downloaded

- Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)

- Under *Installers* select **RStudio x.yy.zzz - Windows Vista/7/8/10** (where x, y, and z represent version numbers)

- Double click the file to install it

- Once it's installed, open RStudio to make sure it works and you don't get any
  error messages

- Follow the steps in the instructions [for everyone](#for-everyone) at the
  bottom of this page.
  

:::::::::::::::::::::::::

#### macOS

:::::::::::::::: spoiler

## If you already have R and RStudio installed

- Open RStudio, and click on "Help" > "Check for updates". If a new version is
  available, quit RStudio, and download the latest version for RStudio.
  
  - To check the version of R you are using, start RStudio and the first thing
    that appears on the terminal indicates the version of R you are running. Alternatively, you can type `sessionInfo()`, which will
    also display which version of R you are running. Go on
    the [CRAN website](https://cran.r-project.org/bin/macosx/) and check
    whether a more recent version is available. If so, please download and install
    it.

- Follow the steps in the instructions [for everyone](#for-everyone) at the
  bottom of this page.
  

:::::::::::::::::::::::::

:::::::::::::::: spoiler

## If you don't have R and RStudio installed

- Download R from
  the [CRAN website](https://cran.r-project.org/bin/macosx/).

- Select the `.pkg` file for the latest R version

- Double click on the downloaded file to install R

- It is also a good idea to install [XQuartz](https://www.xquartz.org/) (needed
  by some packages)

- Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)

- Under *Installers* select **RStudio x.yy.zzz - Mac OS X 10.6+ (64-bit)**
  (where x, y, and z represent version numbers)

- Double click the file to install RStudio

- Once it's installed, open RStudio to make sure it works and you don't get any
  error messages.

- Follow the steps in the instructions [for everyone](#for-everyone) at the
  bottom of this page.
  

:::::::::::::::::::::::::

#### Linux

- Follow the instructions for your distribution
  from [CRAN](https://cloud.r-project.org/bin/linux), they provide information
  to get the most recent version of R for common distributions. For most
  distributions, you could use your package manager (e.g., for Debian/Ubuntu run
  `sudo apt-get install r-base`, and for Fedora `sudo yum install R`), but we
  don't recommend this approach as the versions provided by this are
  usually out of date. In any case, make sure you have at least R 3.5.1.
- Go to the [RStudio download
  page](https://www.rstudio.com/products/rstudio/download/#download)
- Under *Installers* select the version that matches your distribution, and
  install it with your preferred method (e.g., with Debian/Ubuntu `sudo dpkg -i rstudio-x.yy.zzz-amd64.deb` at the terminal).
- Once it's installed, open RStudio to make sure it works and you don't get any
  error messages.
- Follow the steps in the [instructions for everyone](#for-everyone)

#### For everyone

- After installing R and RStudio, you need to install the `tidyverse` and
  `RSQLite` packages. Start RStudio by double-clicking the icon and then type:
  `install.packages(c("tidyverse", "RSQLite"))`. You can also do this by going to Tools -> Install Packages and
  typing the names of the packages you want to install, separated by a comma.



## Software

| Software            | Install                         | Manual | Available for         | Description                                               | 
| ------------------- | ------------------------------- | ------ | --------------------- | --------------------------------------------------------- |
| Spreadsheet program | [Link](https://www.libreoffice.org/download/download/)                                | [Link](https://documentation.libreoffice.org/en/english-documentation/)       | Linux, MacOS, Windows | Spreadsheet program for organizing tabular data.          | 
| OpenRefine          | [Link](http://openrefine.org/download.html)                                | [Link](http://openrefine.org/documentation.html)       | Linux, MacOS, Windows | Program for reproducibly cleaning data.                   | 
| R                   | See install instructions below. |        | Linux, MacOS, Windows | Programming language for data analysis and visualisation. | 
| RStudio             | [Link](https://www.rstudio.com/products/rstudio/download/#download)                                | [Cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf)       | Linux, MacOS, Windows | Integrated development environment for R.                 | 
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


