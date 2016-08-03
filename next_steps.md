# Things we haven't told you

You've come a long way! You've installed and configured all the software you need and have learned the basics required to put your code under version control and make it openly available to the world.

As you've seen, the standard git workflow is fairly straightforward and adds very little overhead to your workflow once you're set up. 

Git and github are extremely powerful systems and there is a lot more you can learn if you wish. Here are some pointers:-

* Learn command line git by following this tutorial from Software Carpentry - http://swcarpentry.github.io/git-novice/
* Make your analysis citable and more discoverable by using Zenodo to assign it a Digital Object Identifier - https://zenodo.org/features

**Testing and version control**

By employing testing, you can ensure that your code behaves the way you expect.

* Unit testing in R, the bare minimum - http://www.johnmyleswhite.com/notebook/2010/08/17/unit-testing-in-r-the-bare-minimum/
* Continuous Integration. Every time you push a change to github, your tests are automatically run. - https://docs.travis-ci.com/user/languages/r

**Dealing with dependencies**

Your code works on your machine but not on someone else's because they are using a different version of R and have different versions of packages installed. How might be fix this?

* https://rstudio.github.io/packrat/ - Packrat enhances your project directory by storing your package dependencies inside it.
* https://mran.microsoft.com/ - MRAN, The 'Managed CRAN' has snapshots of every package going back to 2014

