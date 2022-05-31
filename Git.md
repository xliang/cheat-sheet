## Branch 

| Command | Description |
| --- | --- |
| `git branch -a` | List All branches |
| `git branch --all` | Fetch all remote branches from local |
| `git fetch origin` |  | 
| `git remote update origin --prune` | Refresh the remote branches | 
| `git checkout --track origin/branch_name` | Check out a remote branch | 
| `git checkout -b [name_of_new_branch]` | Create a branch |
| `git push origin [name_of_new_branch]` | Push the branch to github |  
| `git branch -D origin/v2.6.1` | Delete a local branch | 
| `git branch -D <branch_name>` | Delete a local branch |
| `git push --delete origin existing_branch` | Remove a remote branch |
| `git push origin --delete v2.6.2` | Delete remote branch |
| `git merge existing_branch_name` | Combine the specfied branch into the main branch |
| `git merge --no-ff existing_branch_name` | Create a merge commit |
| `git merge --abort` | abort a confliciting merge |





## Tag

| Command | Description |
| --- | --- |
| `git tag` | List all of the tags in the branch |
| `git checkout -b <New Branch Name> <TAG Name>` | Create branch from tag |
| `git tag -a tag_name -m "message"` | Create  a tag | 
| `git push --follow-tags` | Push a tag | 
| `git tag -d <tag_name>`| Delete a local tag |
| `git ls-remote --tag`| List remote tags |
| `git push --delete origin tagname`| Delete a remote tag |

## Changes
| Command | Description |
| --- | --- |
| `git reset --hard` | Reset the changes |
| `git reset --hard origin/master` | Reset to the remote branch | 
| `git reset HEAD~1` | unstaged changes after reset |
| `git revert 1af17e` | Rollback a particular commit  |
| `git stash` | Temporarily park (stash) your uncommitted changes |
| `git stash pop` | Re-apply the changes parked using the stash command |
| `git pull` | Retrieve the changes |
| `git add .` | Add all of the files | 
| `git push` | PUsh your changes to remote repository|
| `git log -p` | View the changes |
| `git log --graph --oneline --decorate` | View commit log as a graph for the current branch |
| `git show 1af17e73721dbe0c40011b82ed4bb1a7dbe3ce29` | View a commit  |
| `git show 1af17e` | View a commit using a short hash  |
| `git diff` | View changes before commit  |
| `git diff --staged` | View the staged changes  |
| `git diff filename.js` | View the changes of a specific file  |


## Config 

| Command | Description |
| --- | --- |
| `git config --global user.name` | Set up user name |
| `git config --global user.email` | Set up email |
| `git config --global credential.helper cache` | Cache login credentails |
| `git config --global credential.helper wincred` | Global Configuration |
| `git config --global credential.helper store` | Global Configuration |
| `git config --get remote.origin.url` | Show Remote URL |


