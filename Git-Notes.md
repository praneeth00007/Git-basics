We use git for version control system ,

git init : it is to initialize a empty git repository
git status : we get status of files in the repo

git add is to add files in repo to prepare for the commit .

git add . ==> to add all files in current directory

git add --all ==> to add all files of ent working tree incl higher directories

to commit the files we need to use git commit 


and lets say after an initial commit , we had changed the data 
we can use 

git commit -am "Commit msg"


we use git branch to create branches and know which branch we are :

git branch

git branch Main

git remote --v : for getting the repo url we used we mainly use repo name as "origin" 


Hey we use git fetch to fetch the remote code i.e github hosted code
To fetch the code : git fetch

u can see the code is not fetched , u need to get the code by using git merge branch name ie the name is origin/branch-name

To delete a branch we use "git branch -d b-name"