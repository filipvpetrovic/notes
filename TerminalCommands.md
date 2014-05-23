Adding a GitHub commands on your Project: Commands and Explanations
======================================

This document is meant to describe the steps needed to successfully
add github to your project. This is the stuff I have learn during my placement here and I would like to share them with you.

##Guidlines on how to create a repo on github!!

First navigate to directory with `cd name`, if there is not existe make it by `mkdir name`! Make sure that after creation you will navigate to this directory by `cd name` and then type:

```c
git init  "add to this application git"
ls -la  "list long all"
ls man "shows you the manual of list"
git add example.txt "add example.txt on git"
git status "shows the status of git"
git commit -m "WRITE YOUR OWN COMMENT" "commit the changes"
git push -u origin master "push it to the original repo"
```

Code on how to clone one project and add it into new branch
```c
git clone require './app'
git clone git@github.com:filipvpetrovic/notes.git
cd notes
git checkout -b branchone
git branch
ls
gedit TerminalCommands.md
git status
git diff
git add TerminalCommands.md
git commit -m 'Title Changed'
git status
git push -u origin branchone
history
git remote -v
git remote add upstream git@github.com:EGiataganas/notes.git
git remote -v
git fetch upstream 
git branch 
git branch -a
git checkout master 
git rebase upstream/master
git log
git push -u origin master 
```

Some helpfull info about git commands
```c
history > myhistory "it adds your command's history into a text file called myhistory"
git log "shows you the log"
git log --oneline "shows you the log in 1line"
git remote add origin git@github.com:dotemacs/nameExample.git "give an explanation"
cd .. "kdf"
```

If we want to use heroku
```c
heroku login "it logs you in"
heroku create "creates the 1st app"
git push heroku master "it push the app into heroku"
heroku open "open site"
```