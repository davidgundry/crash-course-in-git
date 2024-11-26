# Summary of Commands

## Configuration

Set user information key/value pairs. The `--global` flag means this information is shared by all repositories you work with. This information is saved with each commit you make.

    git config --global user.name "Your Name"
    git config --global user.email "your_email@whatever.com"

## Setting up a repository

Cloone a repository from a URL

    git clone <URL> <folder>

Create an empty repository

    git init

Rename branch to GitHub's default of `main`

    git branch -M main

Add a remote (called `origin`)

    git remote add origin <repository-url>

Change the url to a remote (called `origin`)

    git remote set-url origin

Remove a remote (called `origin`)

    git remote remove origin

## Staging and committing changes

Stage changes for commit

    git add .

    git add <filename>

    git add --all

Unstage all staged files

    git reset

Commit changes

    git commit -m "<Message>"

Add currently staged changes to the previous commit

    git commit --amend

## Pulling and pushing changes

Pull changes from the remote

    git pull

Push, setting upstream for branch to point to `main` branch on `origin`

    git push -u origin main

## Working with Branches

Create a new branch called `<name>`

    git branch <name>

Switch to the branch called `<branch>`

    git checkout <branch>

Merge the named branch into the current branch

    git merge <branch>

## Working with history

Show a history of commits

    git log
