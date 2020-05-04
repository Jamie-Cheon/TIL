git init
- create a new local repository

git status
- list the files that you've changed and those you still need to add or commit 

git clone /path/to/repository
- create a working copy of a local repository

git add <file> | git add *
- add one or more files to staging

git commit -m "Commit message"
- commit changes (but not yet to the remote repository)

git commit -a
- commit all files that added with git add / all files that changed since then 

git push origin master
- send changes to the master branch of remote repository

git remote add origin <server>
- connect your local repository to a remote server
- add the server to be able to push to it 

git remote -v
- list all currently configured remote repository

git branch 
- list all the branches in your local repo, and also tell you what branch you're currently in. 

git branch -r
- list all the branches in your remote repo 



   
