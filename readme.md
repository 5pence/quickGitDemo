# My first git thing

## Git commands

- `git init` initialise a new git area / repo
- `git status` get the latest status of your local git
- `git add <filename or .>` add file/s to staging area
- `git commit -m "Good short message"` commits staged files into local git with commit message
- `git log` gets the 'ships log' of all changes to git
- `git config --global user.name "Your name"`
- `git config --global user.email "Your email"`
- `git branch` shows you what branch you are on and what branches there are
- `git push` pushes commits to remote (Github)
- `git pull` pulls latest from remote
- `git merge <branch>` merges tha named branch into the branch you are currently in.

So in teams....

Anytime you hear someone has made apull requests and added things into the main branch you must (to make your life easy) locally

- add your latest changes from your own branch and commit
- checkout your main branch
- git pull the latest remote main into your local main
- checkout your own branch again
- `git merge main` in order to update your local branch with the latest main

That way whenever you want to make a pull request and merge your branch into main (on remote) it ought to always be able to without merge conflicts

