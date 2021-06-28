## Installing R, RStudio and git

Many users of R use it from within another free piece of software called **RStudio.**
RStudio is a powerful and productive user interface for R. It’s free and open source, and works great on Windows, Mac, and Linux.

Rstudio's version control functionality is provided by yet another software called **git**

Our first task, therefore, is to install R, RStudio and git.

**Install R**

Install R first. Downloads are available at <a href="https://cran.rstudio.com/" target ="_blank">https://cran.rstudio.com/</a>  
  * Direct link for Windows <a href="https://cran.r-project.org/bin/windows/base/" target ="_blank">https://cran.r-project.org/bin/windows/base/</a>  
  * Direct link for MacOS X <a href="https://cran.r-project.org/bin/macosx/" target ="_blank">https://cran.r-project.org/bin/macosx/</a> 
  * Direct link for Linux <a href="https://cran.r-project.org/bin/linux/" target ="_blank">https://cran.r-project.org/bin/linux/</a> 

**Install RStudio**

Next, install RStudio.

* Downloads are available at <a href="https://www.rstudio.com/products/rstudio/download/" target ="_blank">https://www.rstudio.com/products/rstudio/download/</a> 

**Install git**

Git is one of the most popular version control systems in the world. It is free and open source.

* Windows & OS X: <a href="http://git-scm.com/downloads" target ="_blank">http://git-scm.com/downloads</a> 
* Debian/Ubuntu: `sudo apt-get install git-core`
* Fedora/RedHat: `sudo yum install git-core`

**Configure git**

After installing git, you need to tell it who you are. Open a terminal window (**cmd.exe on windows**) and type the following

```
git config --global user.email "you@youremail.com"
git config --global user.name "Your Name"
```

On succesful completion, you should see no output from these commands.  

***

[Previous](./README.md) | [Next](./github.md)
