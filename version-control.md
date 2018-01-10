# Introduction to Version Control

A **version control system** is a tool that lets you track the history and attribution of your project files over time which helps with project management and keeping track of development with multiple contributors.  Modern version control systems help teams work simultaneously by giving each developer his or her own sandbox and preventing their work in progress from conflicting. While also providing a mechanism to merge changes and synchronize work.

**Distributed version control systems**, like Git, give each developer their own clone of the repository which also tracks the project's history.

#### Push

The **push **command indicates to Git where your repository is located and allows you to **push **those changes when you're ready.

> **git push -u \[remote repo name\] \[branch name\]**
>
> \(The **-u** tells Git to remember the parameters.  So that next time we can simply run **git push**.\)

#### Pull

When you open a _pull request_, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show differences \(_diffs_\) of the content from both branches.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

The **pull **command allows us to check for changes in the repository and pull down any new changes.

> **git pull \[remote repo name\] \[branch name\]**

#### Differences

The **git diff** command allows you to see what changes have been made to thd repository since your last commit.

> **git diff HEAD**
>
> \(**HEAD **is a pointer that holds your position within all your different commits.  By default **HEAD **points to your most recent commit, so it can be used as a quick way to reference that commit without having to look up the SHA.\)

**Git diff** can also be used to see changes in files that are in the staging area.

> **git diff --staged**

#### Reset

In order to remove files from the staging area use **git reset.**

> **git reset \[file name or file path\]**

To revert files/directories back to a previous commit use **checkout.**

> **git checkout -- \[file or directory\]**
>
> \(The **"--"** signify's there are no more option after the command.\)







