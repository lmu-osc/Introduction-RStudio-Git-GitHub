# Subsequent updates

Once a local repository has been associated with GitHub, it's not necessary to use the command line for subsequent uploads. We'll demonstrate this now by adding a **README.md** file to our project.

On GitHub, the README.md file is special since it is rendered by GitHub and is used by many people as an introduction to the project.

In RStudio, click on **File->New File->Text File**.  Add the following text to the file and save it as **Readme.md**.

```
# My Example Repo

This repo is used to demonstrate GitHub to users of R and R Studio.
```

In the **git** tab of RStudio, the **Readme.md** file should be the only file you see. Stage it as shown below and click **commit**.

![](./assets/staged_readme.png)

Supply a commit message and click commit.

![](./assets/readme_commit.png)

Finally, click **push** to upload to GitHub.

![](./assets/git_push.png)

You can see that the standard workflow loop is very quick and simple

* Make your change
* Stage your change
* Commit
* Push to GitHub  

***

[Previous](./github_sync.md) | [Next](./next_steps.md)
