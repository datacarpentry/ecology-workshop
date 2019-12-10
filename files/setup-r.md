### R and RStudio

* R and RStudio are separate downloads and installations. R is the
underlying statistical computing environment, but using R alone is no
fun. RStudio is a graphical integrated development environment (IDE) that makes
using R much easier and more interactive. You need to install R before you
install RStudio. After installing both programs, you will need to install 
some specific R packages within RStudio. Follow the instructions below for
your operating system, and then follow the instructions to install
**`tidyverse`** and **`RSQLite`**.

#### Windows

> ## If you already have R and RStudio installed
>
> * Open RStudio, and click on "Help" > "Check for updates". If a new version is
> available, quit RStudio, and download the latest version for RStudio.
> * To check which version of R you are using, start RStudio and the first thing
>  that appears in the console indicates the version of R you are
>  running. Alternatively, you can type `sessionInfo()`, which will also display
>  which version of R you are running. Go on
>  the [CRAN website](https://cran.r-project.org/bin/windows/base/) and check
> whether a more recent version is available. If so, please download and install
> it. You can [check here](https://cran.r-project.org/bin/windows/base/rw-FAQ.html#How-do-I-UNinstall-R_003f) for
> more information on how to remove old versions from your system if you wish to do so.
{: .solution}

> ## If you don't have R and RStudio installed
>
> * Download R from
>  the [CRAN website](https://cran.r-project.org/bin/windows/base/release.htm).
> * Run the `.exe` file that was just downloaded
> * Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
> * Under *Installers* select **RStudio x.yy.zzz - Windows Vista/7/8/10** (where x, y, and z represent version numbers)
> * Double click the file to install it
> * Once it's installed, open RStudio to make sure it works and you don't get any
> error messages.
{: .solution}


#### macOS

> ## If you already have R and RStudio installed
>
> * Open RStudio, and click on "Help" > "Check for updates". If a new version is
>	available, quit RStudio, and download the latest version for RStudio.
>	* To check the version of R you are using, start RStudio and the first thing
>	  that appears on the terminal indicates the version of R you are running. Alternatively, you can type `sessionInfo()`, which will 
>	also display which version of R you are running. Go on
>	  the [CRAN website](https://cran.r-project.org/bin/macosx/) and check
>	  whether a more recent version is available. If so, please download and install
>	  it.
{: .solution}

> ## If you don't have R and RStudio installed
>
> * Download R from
>   the [CRAN website](https://cran.r-project.org/bin/macosx/).
> * Select the `.pkg` file for the latest R version
> * Double click on the downloaded file to install R
> * It is also a good idea to install [XQuartz](https://www.xquartz.org/) (needed
>   by some packages)
> * Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
> * Under *Installers* select **RStudio x.yy.zzz - Mac OS X 10.6+ (64-bit)**
>   (where x, y, and z represent version numbers)
> * Double click the file to install RStudio
> * Once it's installed, open RStudio to make sure it works and you don't get any
>   error messages.
{: .solution}

#### Linux

* Follow the instructions for your distribution
 from [CRAN](https://cloud.r-project.org/bin/linux), they provide information
 to get the most recent version of R for common distributions. For most
 distributions, you could use your package manager (e.g., for Debian/Ubuntu run
 `sudo apt-get install r-base`, and for Fedora `sudo yum install R`), but we
 don't recommend this approach as the versions provided by this are
 usually out of date. In any case, make sure you have at least R 3.5.1.
* Go to the [RStudio download
  page](https://www.rstudio.com/products/rstudio/download/#download)
* Under *Installers* select the version that matches your distribution, and
   install it with your preferred method (e.g., with Debian/Ubuntu `sudo dpkg -i
   rstudio-x.yy.zzz-amd64.deb` at the terminal).
* Once it's installed, open RStudio to make sure it works and you don't get any
   error messages.

* After installing R and RStudio, you need to install the `tidyverse` and
`RSQLite` packages. Start RStudio by double-clicking the icon and then type:
  `install.packages(c("tidyverse", "RSQLite"))`. You can also do this by going to Tools -> Install Packages and 
  typing the names of the packages you want to install, separated by a comma.
