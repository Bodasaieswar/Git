# Git
Git Distribution System

## Creating Repository 

    ﹩git init OR git init *name_of_repo* -:  Turns current project directory into a Git repository with the mentioned name

    ﹩git clone *URL/of/repo* -: copy all contents of repo into your machine 


## Tracking changes in Repository 

    ﹩git status -: List of all newly created and edited files that are not yet committed

    ﹩git log -: Gets a list of all commits(with there id) made so far

    ﹩git diff -: Shows changes in files that are not yet staged

    ﹩git show head -: Shows the position of head on the given commit


## Changes in Repository 

    ﹩git add *file-name* -: add changes in this file to staging area 

    ﹩git add . -: Add all changes in every file to staging area

    ﹩git stash -: Saves staged changes as draft

    ﹩git commit -m "comment" -: Comment for the changes made 

    ﹩git reset --hard *commit_id* -: Roll back all the changes until this commit "id" in your local as well as in

    ﹩git revert *commit_id* -: Undo changes to a particular commit in staging area 


## Synchronise Changes

    ﹩git fetch -: Get all latest changes made in remote

    ﹩git pull -: Pulls all new changes from remote to your local copy

    ﹩git push -: Pushes all your local committed changes to remote 📌


## Managing Branches  

    ﹩git branch -: Lists all branches present in your local copy

    ﹩git branch -av -: Lists all branches present in your local & remote

    ﹩git branch *name* -: Makes new branch with the mentioned name

    ﹩git checkout *branch_name* -: Switch to the mentioned branch

    ﹩git branch -d *branch_name* -: Delete the mentioned branch from local copy

    ﹩git push origin *branch_name* -: Pushes mentioned branch to remote

    ﹩git checkout *branch_A* -: Merges branch B into branch A
    
    ﹩git merge *branch_B*


## Misc

    .gitignore -: It's a file in your project , you can add name of any file or folders you don't want to be pushed on the remote branch eg. log files , dependencies etc. 

    ﹩git -: Shows all github commands
