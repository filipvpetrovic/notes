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


Clone a repo

    git clone git@github.com:filipvpetrovic/notes.git

cd notes
create and switch to this bra
    git checkout -b branchone
list what branch
    git branch 
gedit TerminalCommands.md //create file or open if exist
git push -u origin branchone //push the changes up
git remote -v //shows you where your repo is
git remote add upstream git@github.com:EGiataganas/notes.git  //synch it
git fetch upstream 
git branch -a //list all the branches
git checkout master // checkout the changes to master repo
git rebase upstream/master // ??
git push -u origin master // push everything to master
```

Some helpfull info about git commands
```c
history > myhistory "it adds your command's history into a text file called myhistory"
git log "shows you the log"
git log --oneline "shows you the log in 1line"
git remote add origin git@github.com:dotemacs/nameExample.git "give an explanation"
cd .. "kdf"
cd - "jkdj"
git mv gitHub\ Commands TerminalCommands "kdhk"
```

If we want to use heroku
```c
heroku login "it logs you in"
heroku create "creates the 1st app"
git push heroku master "it push the app into heroku"
heroku open "open site"
```