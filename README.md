# Crash Course in Git

## Introduction

Git is an essential skill in modern software development. In this Crash Course in Git, you will learn the basics of using Git via the command line. While there are many GUIs to help you use git, this crash course focuses on the command line for these reasons:

1. Command line usage can be easier and quicker once you are comfortable with it.
2. It exposes more clearly the concepts underpinning Git, which was originally designed with the command line in mind.
2. Git can do many things, and often it is only possible to do these via the command line. Even if you don't use the command line for Git day to day, it is valuable to know the basics of how to do so so that you are familiar with it if you are ever forced to use it

This crash course consists of an accompanying [presentation](./crash-course-in-git.pdf) and a tutorial with a set of challenges for you to complete. You might not complete them all during the session. This repository will remain available for you to work on after the session.

#### Lecture Recording

If you have a York St John University account, you can access a [recording of the presentation](https://yorksj-my.sharepoint.com/:v:/g/personal/d_gundry_yorksj_ac_uk/ERUC1UGuADNNoROVGqzakJgBoOBDKAe5aOzb-tpeQ6RUCA?e=I4Bd0c&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D).

### Learning Outcomes
1. Explain the motivation behind using version control
2. Describe key terminology and concepts in the use of git
3. Perform basic git tasks on the command line
    1. Create a repository
    2. Commit changes
    3. Push changes
4. Perform basic tasks for collaboration on GitHub
    1. Create a repository
    2. Configure authentication
    3. Fork a repository
    4. Create a Pull Request

### Additional Resources

* [Frequently Asked Questions](./faq.md)
* [Summary of Important Commands](./summary-of-commands.md)
* [Quiz](./quiz.md)

### Helpful Links

* [Github Docs](https://docs.github.com/en/get-started)

## Level 0 - Sign up for GitHub

In this crash course we will be using GitHub. There are other Git hosts available if you prefer. While most of the basics of Git will be the same, how you authenticate with the git server, and how you create and work with git repositories on the host may be different.

Before you start levelling up your skill in Git, sign up for an account on GitHub (https://github.com) ([documentation](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github)). 

## Level 1 - Practice  the basics of Git

Get the basic level of Git proficiency by working through the tutorial. This will get you to set up Git, create a repository, push it to a remote, and clone it.

1. [Configuring Git](./1-configuring-git.md)
2. [Creating a Repo](./2-creating-a-repo.md)
3. [Set a remote and push](./3-set-remote-and-push.md)
4. [Clone a repo](./4-clone-a-repo.md)

Once you have completed the tutorial, try to complete the challenges below and level up your ability with Git.

## Level 2 - Start using Git for personal projects

The best way to learn git is to start using it in your day to day work. 

Pick an existing project if you have one and create a git repository for it. As you already have files, the best way to do this is to initialise a git repository in the existing project folder.

1. Initialise a git repository in a folder of your choice on your computer
2. Create a repository for it on GitHub
3. Push your files to the remote repository

As you work on this project in the future, track your changes by making commits and pushing them to the remote repository.

Get into good habits now. Before you move on, make one small change to your project, commit it with a helpful mesage, and push your changes.

## Level 3 - Collaborate using Pull Requests

Git and GitHub is used in the Open Source software community for collaboration. Here we are going to see a key feature of GitHub for collaboration - forks and pull requests.

The instructions you are currently reading are hosted in a git repository on GitHub. This repository could be improved and extended. You, as a person who now knows how to use Git can do this.

To keep it easy for now, take a look at the file [`quiz.md`](./quiz.md). This file contains quiz questions that can be used in future deliveries of the presentation to help students learn Git. Your challenge is to add a question to this file.

On the Github repository page, find the button and dropdown labelled `Fork` (at the top right). Click `Create a new fork`.

Clone your fork to your local machine. In the `quiz.md` file add a new quiz question and answer. Make a commit of your changes and push this commit to your forked repository.

Back on GitHub, create a pull request to ask for your questions to be added to the original repository.

* [Pull Requests Documentation](https://docs.github.com/en/pull-requests)
* [Pull Requests on GitHub Tutorial](https://docs.github.com/en/get-started/start-your-journey/hello-world)
