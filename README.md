# Table of Contents

- [Getting Started](#getting-started)
- [Setting up softwares](#setting-up-softwares)
- [Setting up git](#setting-up-git)
- [Forking and Cloning](#forking-and-cloning)
- [Making branches](#making-branches)
- [Editing files](#editing-files)
- [Adding and commiting changes](#adding-and-commiting-changes)
- [Pushing changes and submitting a Pull Request](#pushing-changes-and-submitting-a-pull-request)

# Getting Started

This repo is to help newbies get started with open source. The objective of this tutorial is to make your first Pull Request and add your name to the [contributors](contributors/) folder. If you get stuck, ask your doubt on the [NWoC Gitter Channel](https://gitter.im/NWoC/NWoC2018).

## Setting up softwares

To work on Github hosted projects, one has to use Git - a Version Control System. So the first task is to install git on your machine. For Windows users, download git from here - https://git-scm.com/downloads. For Linux users, you can use your distro's package manager to install git.

**Note:** Although Linux isn't mandatory, it is preferred while working with Open Source Software.

**Note:** You can learn about Version Control Systems (VCS) [here](https://www.atlassian.com/git/tutorials/what-is-version-control).

### Setting up git

After installing git, run git and execute these commands:

```
git config --global user.name "[name]"
git config --global user.email "[email address]"
```

That should complete the software setup.

## Forking and Cloning

Before you can edit any file on the repo, you must fork and clone it. A **fork** is a copy of the repository in your account. To **clone** a repo means to download it locally. Click the Fork button on the top right of this repo to fork it. Next, go to your copy of the repo and click the Clone button. Copy the url. Now open git and execute this command:

```
git clone [copied url here]
```

That should download the repo locally.

## Making branches

A **branch** is a parallel copy of the code. When we add new features to a project, we usually create a copy of the code and work on it. This is done so that the main working copy of the code is unaffected. In most GitHub repos, the master branch is the default branch. You should create a separate branch for every contribution you make. To create a new branch, execute this command:

```
git checkout -b [branch name here]
```

You should see the branch name change on the terminal prompt. Congratulations! You created a new branch.


## Editing files

Create a new text file in the [contributors](contributors/) folder with your github handle as the file name. This file should contain your name. A sample file [aryadas98.txt](contributors/aryadas98.txt) has been provided.

## Adding and commiting changes

To create a **commit** means to save your work. But before you commit, you have to **add** your work to the commit. To do so, execute this command from the project root:

```
git add *
```

This adds all files to the upcoming commit. Now, to create the commit run this command:

```
git commit -m "[commit message here]"
```

Write any message in place of the commit message. If the command runs successfully, you should have committed your changes.

## Pushing changes and submitting a Pull Request

After committing you chanegs, you have to upload them to GitHub. This is known as **pushing**. To push your changes, run:

```
git push origin [branch name]
```

Where branch name is the name of your newly created branch. This should upload your changes to *your* GitHub account. Now, you can propose these changes to the actual project. To do so, click on the **Pull Request** button on GitHub. Most of the fields should be automatically filled out for you. Click Create Pull Request. If everything went correctly, you should have created a pull request with your changes. Now it is upto the repo owner to **merge** these changes.

Congratulations! You made your first Open Source Contribution! Now contribute to some other repos on NWoC. Have a great time!
