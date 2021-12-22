# Git-Commands #

### Working Area		: area where we create and modify the files.
### Staging area		: area between the Working Area and the Local Repository Area.
### Local Repository Area: area where the repository is.

git init # to create a new empty git project

git status # see the git status

git add filename # to add each file separately to the Staging Area. OR...

git add . # to add all files to the Staging Area

git rm filename # to remove file form working area

git commit -m "message" # commit all the files in the Staging Area to the Local Repository

git log # see what commits have been made

git diff filename # see the difference between the file in the Working Area and the corresponding file in the local Repository area

git checkout filename # roll back to the previous version of the file; overwrites the working area file with the local Repository file version

### After creating a remote repository on GitHub or somewhere else, one firstly adds the remote repository.
git remote add origin xxx # where xxx is the name of the remote repository 

### And then one pushes the local repository to the remote repository.
git push -u origin master # push repository to the master branch

### OR firstly create a branch, and then push the local repository to that branch
git branch -M main        # create branch firstly

git push -u origin main   # push repository to the corresponding remote branch, in this case the main branch
