# Git
## What is git?
Free and open source version control system, free and open source 
## What is version control? 
A way thet we as programmers track out code changes, we basically save an initial version of our code into git an then update code we can save it into git again 
and throughout time as out code continues to change we can look back at all the changes we admit over time
this helps us to see and understand what we did when as weel as track down bugs or go back to a previous version of the code if ewe need to
## Term
- Directory -> Folder
- Terminal or command line -> inferface for text commands, basically mean an application that runs on your computer
wich is just an interface where you cna type in text commands. Your can navigate in folders 
crreate folders create files change update things install and runs programs and much more
- CLI: Command Line Interface. Many programmerss that you install as a programmer wil lrequire you to interat with them via text commands in the command line
- cd: change directory
- Code editor -> word processor for writing code
- Repository -> Project or the folder / place where ypur project is kept
- Girhub -> A website to host your repositories online
## Git commands
- Clone -> Bring a repository that is hosted somewhere like Github into a folder on your local machine
- add -> track your files and changes in Git 
- commit -> track your files and changes in git
- push: upload Git commits to a remote repo, like github
- pull -> download changes from remote repo yto your local machine the opposite of push

## Notes:
- every commit has an indentifier
- we can open git

## Git Bash
- git -- version -> to know the version 
- 

## movifications
-- git status: showns me all of the files that were updated or created or deletes but haven't been saved in a commit yet
    - can be appear 'Changes not staged for commit:' or 'Untracked files:' (git doesnñt know about this file yet) 
- git add -> tell it which files to track now most of the time or a lot of the time you see people use a '.' (track all of the files that are listed here)
- git commit -m -> -m is for messages, you nee dto have a message in order to commit your files, the message could be one caracter in meaningless if you want but there needs to be 
    - in a commit message there are two boxes we can put the second one as follows: 
        - git commit -m "Message 1" -m "Message 2"
            - bue after that we saved our code locally, the commit isn't live on girhub yet we make it live by using 'git push'
- git push -> I want topush this live to a remote repository wher e my project is hosted
    - git push origin: origin is the location of our git rrepodsitory and master is the branc that we want to push to 