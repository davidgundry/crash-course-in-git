# Summary of Commands

Create a repository

    git init

Add a remote

    git remote add origin <repository-url>

Rename branch to GitHub's default

    git branch -M main

Stage changes for commit

    git add .

Commit changes

    git commit -m "<Message>"

Push, setting upstream for branch

    git push -u origin main


Create a new branch called `<name>`

    git branch <name>

Switch to the branch called `<branch>`

    git checkout <branch>

Merge the named branch into the current branch

    git merge <branch>

Unstage all staged files

    git reset

Show a history of commits

    git log

Add currently staged changes to the previous commit

    git commit --amend
