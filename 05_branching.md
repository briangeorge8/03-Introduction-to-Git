# Cloning and Branching

<a href="https://github.com/CyberTrainingUSAF/03-Introduction-to-Git/blob/master/00-Table-of-Contents.md" rel="Return to TOC"> Return to TOC </a>

In order to start working on an existing project and creating a branch you will first have to **clone **the repository on your local machine.

> **git clone \[remote repository URL\]**

**Branching** is the way to work on different versions of a repository at one time.

When you create a branch off the master branch, you’re making a copy, or snapshot, of the master repository as it was at that point in time. If someone else made changes to the master branch while you were working on your branch, you could pull in those updates.

This diagram shows:

* The master branch
* A new branch called feature \(because we’re doing ‘feature work’ on this branch\)
* The journey that feature takes before it’s merged into master

![](/assets/17.PNG)To create a new branch:

> **git branch \[new branch name\]**

To have git point to the new branch:

> **git checkout \[branch\]**

To create a new branch and point to it:

> **git checkout -b \[new branch name\]**

To move files or folders:

> **git mv \[target destination\]**

To remove files from the new branch you can use:

> **git rm \[file name\]**
>
> \(You can also use the **-r** option to recursively remove all files and folders from a directory\)

To make a directory:

> **git mkdir \[name of directory\]**

To "save" changes:

> **git commit -a -m "Message"**
>
> Use **-a** for all, **-m** to add a message.

<a href="https://github.com/CyberTrainingUSAF/03-Introduction-to-Git/blob/master/06_version_control.md" rel="Continue to Next Topic"> Continue to Next Topic </a>

