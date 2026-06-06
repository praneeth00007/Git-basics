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

We use one command for fetch,merge ie "pull" command

ie we use git pull to fetch and merge the branch

we can edit the code and add some features too in github using github code spaces

using "github.dev"

Hey man just learned new concept 

lets say if my main branch had code : "I love main"

and after i had commited and now i had created a new branch test

now if i had switched to test i see same code of main

i shocked when i had updated some code in main " i love main updated"
in test it still shows "i love main"

either u need to merge in order to get the commits or need to use rebase

i understood now maybe lets test

when the both main and other branches had same code and lets say test

and after u had added some more features to test now u had commited 

when u checkout and tried to delete using -d u get erorr

error: The branch 'test' is not fully merged.
If you are sure you want to delete it, run 'git branch -D test'.

wow !

lets made a conflict git