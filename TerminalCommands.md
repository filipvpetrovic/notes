Adding a GitHub commands on your Project: Commands and Explanations
======================================

This document is meant to describe the steps needed to successfully
add github to your project. 

##Guidelines on how to create a repository on github

Firstly you will need to  navigate to the directory `cd name`, if the directory does not exist then a directory will be created and the command line for that is `mkdir name`! However make sure that the directory will navigate you to the correct directory which has been created previously. Once the directory has been acessed you will then type the following. 

```c
Add to this application git
	git init  

list long all
	ls -la  

Shows you the manual of the list
	ls man 

Add example.txt on git
	git add example.txt 

Shows the status of git
	git status 

Commit the changes
	git commit -m "WRITE YOUR OWN COMMENT" 

Push it to the original repository
	git push -u origin master 
```

Code on how to clone one project and add it into new branch
Clone a repo

    git clone git@github.com:filipvpetrovic/notes.git (example of git hub)


In order to creaet and switch to this branch you type
    git checkout -b branchone

In order to list what branch it is you type
    git branch 


Create a file or open if exist
	gedit TerminalCommands.md 

Push the changes up
	git push -u origin branchone 

shows you where your repo is
	git remote -v 

Command used for syncing
	git remote add upstream git@github.com:EGiataganas/notes.git 

Command used to fetch upstream 
	git fetch upstream 

list all the branches
	git branch -a 

Checkout the changes to master repo	
	git checkout master 

???
	git rebase upstream/master 

Pushes everything to master
	git push -u origin master 
```

Some helpfull git commands
```c

It adds your command's history into a text file called myhistory
	history > myhistory 

Shows you the log
	git log 

Shows you the log in 1line
	git log --oneline 

?????	
	git remote add origin git@github.com:dotemacs/nameExample.git 

Brings you too the previous directory
	cd .. "kdf"

Shows how you have gotten to the directory your currently in
	cd - "jkdj"

???
	git mv gitHub\ Commands TerminalCommands "kdhk"
	
???
	git status -sb 

Shows in the terminal what has been committed	
	less README.md 
	
???
	git show -p 

Shows you the entire log
	git log --decorate --all
```

If we want to use heroku
```c

It logs you in
	heroku login 

Creates the 1st app
	heroku create 

It push the app into heroku
	git push heroku master 

Open site	
	heroku open
```