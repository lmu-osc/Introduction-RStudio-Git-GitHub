# Introduction to version control with Git and GitHub within RStudio

## About this work

This work was originally created by [Mike Croucher](https://github.com/mikecroucher) from [RSE-Sheffield](https://github.com/RSE-Sheffield) under a [Creative Commons Attribution Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/legalcode). The [original repository](https://doi.org/10.5281/zenodo.61435) was created for a workshop organised by Malika Ihle at the International Society for Behavioural Ecology conference in 2016.  It was subsequently adapted by Malika for [Reproducible Research Oxford](https://ox.ukrn.org/). It is now maintained by [Malika Ihle](https://www.osc.uni-muenchen.de/about_us/coordinator/index.html) for the [LMU Open Science Center](https://www.osc.uni-muenchen.de/index.html). The overview image is from [Dumitru Uzun](https://duzun.me/tips/git). You are free to use this work in your own projects. 

## Before the session 
Please watch this 10 min introductory [videorecording](https://osf.io/dcqt9/).

## Overview of the exercice  
In this session, you are going to start using the version control system Git from within RStudio to keep your local workflow tidy while having access to all previous versions of your files. You will then backup your workflow online on a remote GitHub server, which will allow you to access your work from any computer, and sharing it with your collaborators or publically. Specifically, you will  
* install and configure Git (as well as R and RStudio if needed), and create a GitHub account  
* create a local RStudio project under version control  
* make changes and **commit** them to your local repository (i.e. save your changes locally in your version control system)  
* connect your local repository to your GitHub account by creating a remote GitHub repository and setting it as the 'origin' of your local repository from the command line (this is the procedure you will have to follow to 'upgrade' your former RStudio projects that were not under version control and backed-up on GitHub; but in the future, I recommend you first create a GitHub repository (your remote origin) and then **clone** it locally (i.e. copy it to your computer while maintaining a connection to your remote (GitHub) version). This procedure, easily done from RStudio, will be covered in the [second workshop](https://lmu-osc.github.io/Collaborative-RStudio-GitHub/))  
* **push** your local changes to your remote repository (i.e. synchronise your changes to your GitHub version)  

Once this workflow is set up, you can easily work with several computers or with collaborators: if you have changes in your GitHub version (if you or a collaborator pushed changes from another computer or if you made changes online, directly on GitHub), you can **pull** them into your local version (i.e fetch changes and merge them locally, to keep your copy up-to-date).

<br/>
<img src="assets/GitHub-remote.png" width="750">  
<br/>

## Step-by-step tutorial
The material is self-paced and includes a worked-example. It is necessary that you work through the sections in order.  

* [Installing R and RStudio](./installing_software.qmd)
* [Installing and configuring Git](./installing_git.qmd) - Set up your own machine
* [Getting an account on GitHub](./github.qmd) - Sign up for GitHub
* [Securing your connection to GitHub](./SSH.qmd) - Create a secure SSH key to identify yourself on GitHub
* [Creating an RStudio project](./rstudio_project.qmd) - Creating an example, version controlled project
* [Starting our analysis project](./analysis_start.qmd) - A simple script to get us started
* [Getting our project under version control](./version_control.qmd) - First step into a larger world
* [Making some changes](./making_change.qmd) - Making our script more useful
* [Committing our change](./commit.qmd) - How to commit a change
* [Viewing history](./viewing_history.qmd) - How to view the history of your project or of a single file
* [Connecting our local repository to GitHub](./github_sync.qmd) - Backup! Making our code available to the world.
* [Subsequent updates](./updates.qmd) - Now we are set up, the workflow is easy.
* [Things we haven't told you](./next_steps.qmd) - Steps to further learning
