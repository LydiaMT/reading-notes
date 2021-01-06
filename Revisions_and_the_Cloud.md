# Revisions in the Cloud
These are my reading notes from [the following article](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

> " Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world."

To use Git, you will first need to install it on your computer as a package, via another installer, or download and compile the source code. The download process in the terminal is slightly different for Mac, Windows, and Linux. If you want to install different Graphical User Interface (GUI) tools, [click here](https://git-scm.com/downloads/guis)

Customize Git with your own name and email address:
* git config --global user.name "your name"
* git config --global user.email "your@email"
* You can confirm your settings by entering the commands once more without the "your name" or "your@email"

If you want more information on a specific command, use the following:
* git help *command*
* git *command* --help
* man git-*command*

### Cloning
To clone something use the following command:
git clone **file location**

This creates a directory with copies of the files for your project

### Local Repository Structure
Your local Git repositry has three components: 
1. Working Directory where the files reside
1. Index for staging
1. Head most recent commit

After editing a file, stage the modified file, then commit staged changes. 

### Helfpul git commands

Command | Explination
------------ | -------------
$ git status | shows you if there are changes to commit or not
git add filename | track one file
$ git add * | track all files
$ git commit -m "explination of changes" | commits file and explains what changed
$ git commit -a | commits a snapshot of all modifications to tracked files in working directory
$ git push origin main | pushes changes from local "main" branch to remote repository "origin" 
git stash | temporarily removes changes and hides them
git stash apply | command to retrieve the hidden changes
git remote | view the short names of all specified remote handles
git remote -v | view all the remote URLs next to their corresponding short names
git remote add short name url | creates new remote Git repository with a short name
git fetch `[remote-name]` | fetches data from your remote projects
git remote rename | renames a remote's short name
$ git commit --amend | Use when you need to alter a commit message or forgot to add some files
git rest HEAD | unstages files
git revert | undo changes resulting from a particular commit
git checkout | have a file return to its state when you last committed it. Be certain before you use this. 
$ git branch  | creates a new branch
$ git checkout | switches you to another branch
git merge | merges branches
git pull | fetches and merges remote changes
$ git branch -d | Deletes branches that are no longer needed after you merge them
git diff | To preview changes from merging
git branch-v | To see newest commits for each branch
git branch --merged | shows you wich branches are already merged into the branch you're on
git branch --no-merged | shows you all branches that contain work you haven't yet merged in
git log | view committed snapshots
git tag | use to flag certain points in a project's history as being significant i.e. v1.0 v2.0. There are lightweight and annotated tags
git push origin --tags | pushes all of your tags out at once
git config | to create aliases

Fewww, that was a lot? Are you a git command expert yet!? :)

### Most Common Distributed Workflows
* Centralized Workflow: Entails the existance of one main hub, which can accept code. 
* Integration-Manager Workflow: Involves multiple remote repositories

*Remember: "origin" is just the default remote name when you use the git clone command*


[⬅ Back to README Home](README.md)