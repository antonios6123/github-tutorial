# GitHub Tutorial

_by Antonio Silva_

---
## Git vs. GitHub

### Git

_Git is a version control system to keep track of work/code._

_Git does not require GitHub._

_Git is the command line to github._

### Github

_Github does require git._

_Github is a website that easily allows people to real time collaborate._

_Github is the cloud where all of the code lives._

_In GitHub you can see what changes you made to commits._

---
## Initial Setup

To start of github you must make an account that has your first name, first letter of last name and the last 4 letters of your OSIS number.

CLick the free plan and click the option that you've never coded before.

After that go to your IDE, sign in and follow the directions in this link.

[Click this link to setup and SSH key between ide50 and Github.](https://github.com/hstatsep/ide50)

All in all this link is just setting up the SSH key and enabling little things within ide to help make the code easier.

Just read the README and follow the directions.

---
## Repository Setup

When you first log on to your ide you are immediately directed in tilde "~" folder.

To make your first repository you must type in `mkdir` and the name.

It would look like this - `mkdir name`.

You must remember the name of this directory because after you make this you are going to go into github.com

Once you are in github you are going to press the "+" sign in the top right and press new repository.

You have to copy the name of your directory in the ide into the "repository name".

You can press "Initialize this repository with a README" if you want a README in your repository.

Then press the green button "Create repository".

Once you create this repository you are able to commit and push whatever you want to it and it will save all of your code!

---
## Workflow & Commands

`git init` - Initalizes git in our directory for version control -- only do this once at the beginning. Cd into the folder you want to be the parent folder, git init, and that becomes the parent folder.

`git add file` or `git add .` - Adds the current/entire directory: all files that have changed (including deleted/renamed files).

`git commit -m ""` - Takes a “snapshot” of files on the stage. -m adds a message to go along with it to help you keep track of what you changed in this commit. Make sure the message is in lowercase letters and in present tense.

`git remote add origin URL` - We are seting up a connection between our current repository and an external one (that lives on github).

`git push` - Sends changes of code from your latest commit on cs50 to a GitHub repository.

`git diff` - See the difference between your current code and the previous commit.

`git log` -  See record of what changed in your past commits to track progress and changes, you have to press Q to get out.

`-u` - Means “upstream”. This tells git to remember which remote repo & branch to push our changes to when we type git push in the future.

`git remote -v` - Tells you where your git push command will send your commits to.

`git status` - Optional command to see which files have been edited since the last commit (will tell you whats different or what changes have been made) , will be in red.

`origin` - This is our “nickname” for the remote repo. “Origin” is standard. In the future, you , might need multiple remotes.

---
## Rolling Back Changes

`rm-rf .git`

Remove the hidden .git folder from the git init command. In other words it unitizializes git.

`git checkout --file`

This command deltes any edits that you make between the current commit and the next one.

`git reset HEAD file`

This command will undo the most recent git add that you have.

`git revert`

This command is one of the most useful commands on git in my opinion, because if you make a mistake you can just get the code for it, `git revert` and you fixed that mistake.
This command is especially useful because no other website has this command.

`git reset --hard [SHA]`

This command will undo a `git push`.
