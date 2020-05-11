git clone [remote repo addr]
- clone a remote repo under working directory

git branch 
- retrieve branches

git branch [new branch]
- create new branch 

git checkout [branch]
- switch to [branch]

git merge [branch]
- merge [branch] back into your current branch 

git branch -D [branch]
- delete [branch]
 
-----------------------------------------------

git flow init
- create develop branch on an existing repo 

git flow feature start [feature name]
- create feature branch 

git flow feature finish [feature name]
- merges [feature name] into 'develop'
- removes the feature branch
- swtiches back to 'develop' branch  

git flow release start [version name]
- create release branch 

git branch -D [version name]
- remove released version 

git flow release finish [version name]
- merges the release branch back into 'master'
- back-merges the release into 'develop'
- removes the release branch 

git push -u origin [branch name]
- create [branch name] into origin server 
- '-u' : if the [branch name] does not exist in the server

---------------------------------------------------

[Team Project]

1. Fork team manager's repo
2. git clone [my remote repo that forked from mgr's repo]
3. move to cloned repo
4. git remote add pmorigin [team mgr's repo addr]
  - in order to pull processing file under team mgr's repo into local branch 
5. git push origin master
6. create pull request in my remote repo to team mgr's repo  

