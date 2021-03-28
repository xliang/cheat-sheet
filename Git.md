```shell

# Reset the changes
git reset --hard 

/* List all branch */
git branch -a 

# Check out a remote branch 
git fetch origin
git checkout --track origin/banch_name

# create a branch
git checkout -b [name_of_new_branch]

# push the branch to github
git push origin [name_of_new_branch]

<<<<<<< HEAD
# List all branch 
git branch -a 

# checkout remote branch 
git checkout --track origin/daves_branch
=======
# delete a local branch 
git branch -D origin/v2.6.1
git branch -D <branch_name>

# delete remote branch 
git push origin --delete v2.6.2

>>>>>>> 921baa3f85429cf759fa1e89596f80ffa458e7ea

```
