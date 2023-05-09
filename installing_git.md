## Installing and configuring Git

RStudio version control functionality is provided by another software called **git**


**Install git**

Git is one of the most popular version control systems in the world. It is free and open source.

* Windows & OS X: <a href="http://git-scm.com/downloads" target ="_blank">http://git-scm.com/downloads</a>
    *  Windows: download the .exe file, run it and accept all the default settings (unless you know what you are doing) and keep clicking 'next'
    *  OS X: at the link above, select the first option that suggests to install git through installing homebrew, by pasting a line of command provided in their instructions in your terminal, and accept the prompts appearing in your terminal.
* Debian/Ubuntu: `sudo apt-get install git-core`
* Fedora/RedHat: `sudo yum install git-core`

**Configure git**

After installing git, you need to tell it who you are.

By default, git is used through a _command line interface_. We'll use
git in this way now in order to perform its initial and minimal
configuration. In the remaining of this tutorial, you'll learn how to
use git through Rstudio instead of a command line interface.

On windows, open **Git Bash** (start menu -> Git Bash). On MacOS, open
the **Terminal** app. On Linux, open your distribution's (or any
other) terminal emulator. Enter the following commands EXACTLY (spaces and quotation marks included) one after the
other (hitting ENTER after each command). On successful completion, you should see no output from these commands. 

Make sure to replace `you@youremail.com` and `Your Name` by your email
address and your name.

```
git config --global user.email "you@youremail.com"
git config --global user.name "Your Name"
```


***

[Previous](./installing_git.md) | [Next](./github.md)
