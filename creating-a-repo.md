# Creating a New Repository

#### Root Repository or Master Branch

![](/assets/12.PNG)

To create a new repository, click "Create a project".

![](/assets/7.PNG)

You can create a repository under your **username **or under a **group**. For now just enter a Respository name and a Description under the** Blank project** tab.

![](/assets/6.PNG)

Initializing a new repository will look like this:

![](/assets/8.PNG)

_copy url for project:  _[_https://gitlab.com/user-name1/test.git_](https://gitlab.com/user-name1/test.git%29\)

The README file can be created with your project. It's optional and can be added later if necessary. Mostly, if you're creating a new repo you'll want to initialize it with a README.  If you already have a repo you're wanting to upload you can skip this step. The README can be used in various ways, but it will allow you and others to clone the project immediately.

Now that we've setup your **GitLab **account and created a new repository, go to: [http://gitforwindows.org/](http://gitforwindows.org/)  to download and install the **Git Bash. **Then navigate to your project folder through the command prompt or Git Bash and type:

![](/assets/9.PNG)

This will create a hidden directory where Git operates.

Next type:

> **git status**

![](/assets/10.PNG)

This will show you the status of your repository and also we can use it to verify Git has initialized correctly.

Next save these Git commands to notepad as a text file.

> **Command line instructions**
>
> Git global setup
>
> git config --global user.name "Robert Jakob"
>
> git config --global user.email "rsjakob@outlook.com"
>
> Create a new repository
>
> git clone [https://gitlab.com/user-name1/test.git](https://gitlab.com/user-name1/test.git)
>
> cd test
>
> touch README.md
>
> git add README.md
>
> git commit -m "add README"
>
> git push -u origin master
>
> Existing folder
>
> cd existing\_folder
>
> git init
>
> git remote add origin [https://gitlab.com/user-name1/test.git](https://gitlab.com/user-name1/test.git)
>
> git add .
>
> git commit -m "Initial commit"
>
> git push -u origin master
>
> Existing Git repository
>
> cd existing\_repo
>
> git remote rename origin old-origin
>
> git remote add origin [https://gitlab.com/user-name1/test.git](https://gitlab.com/user-name1/test.git)
>
> git push -u origin --all
>
> git push -u origin --tags

Now type, **git status. **You should see a message showing an untracked file...

![](/assets/11.PNG)

To tell Git to start tracking changes made to this file, we need to add it to the staging area by using **git add**.

![](/assets/14.PNG)

Now using **git status**, you should see the **"new file".**  The files added are now in the Staging Area.  They have not been committed to the repository.  So we can add and remove these files before storing them in the repository.

To store our staged changes we run the **commit **command with a message describing what we've changed.

![](/assets/15.PNG)

When adding multiple files you can use a wildcard **'\*' **to add them simultaneously.

> **git add '\*.txt'**

Similarly, you can commit multiple files simultaneously.

To see all the changes that have been committed use **git log.**

![](/assets/16.PNG)

To map a remote repository to your local _git config_** **use:** git, remote add, **the _**remote name,**_ and the _**repository url**_.

> **git remote add main **[https://gitlab.com/user-name1/test.git](https://gitlab.com/user-name1/test.git)

_note: it's usually a good idea to name your main repo something obvious like master, main, root, origin, etc..._

For more information on **git config:**

[https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-config](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-config)

