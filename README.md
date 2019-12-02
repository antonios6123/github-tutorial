# GitHub Tutorial

_by Antonio Silva_

---
## Git vs. GitHub

Git is a version control system to keep track of work/ code.

Git does not require github.

Github does require git.

Git is the command line tool to github.

Github is a website that easily allows people to real time collaborate.

Github is the cloud where all of the code lives.

In github you can see what changes you made to commits.

---
## Initial Setup

[Click this link to setup and SSH key between ide50 and Github](https://github.com/hstatsep/ide50)

All in all this link is just setting up the SSH key and enabling little things within ide to help make the code easier.

---
## Repository Setup

When you first log on to your ide you are immediately directed in tilda "~" folder.

To make your first repository you must type in `mkdir` and the name 

It would look like this - `mkdir name`

You must remember the name of this directory because after you make this you are going to go into github.com

Once you are in github you are going to press the "+" sign in the top right and press new repository.

You have to copy the name of your directory in the ide into the "repository name"

You can press "Initialize this repository with a README" if you want a README in your repository.

Then press the green button "Create repository"

Once you create this repository you are able to commit and push whatever you want to it and it will save all of your code!
  
---
## Workflow & Commands

`git init` - Initalizes git in our directory for version control -- only do this once at the beginning. Cd into the folder you want to be the parent folder, git init, and that becomes the parent folder. 

`rm -rf .git` - Remove the hidden .git folder from the git init command

`git add file` or `git add .` - Adds the current/entire directory: all files that have changed (including deleted/renamed files)

`git commit -m` - Takes a “snapshot” of files on the stage. -m adds a message to go along with it to help you keep track of what you changed in this commit.

`git remote add origin URL` - We are seting up a connection between our current repository and an external one (that lives on github)

`git push` - Sends code to external location so it doesn’t take taken down by fire

`git diff` - See the difference between your current code and the previous commit

`git log` -  See record of what changed in your past commits to track progress and changes, you have to press Q to get out

`-u` - Means “upstream”. This tells git to remember which remote repo & branch to push our changes to when we type git push in the future

`git remote -v` - Tells you where your git push command will send your commits to

`git status` - Optional command to see which files have been edited since the last commit (will tell you whats different or what changes have been made) , will be in red.

`origin` - This is our “nickname” for the remote repo. “Origin” is standard. In the future, you , might need multiple remotes

---
## Rolling Back Changes

