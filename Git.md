## Branch 

| Command | Description |
| --- | --- |
| `git branch -a` | List All branches |
| `git branch --all` | Fetch all remote branches |
| `git fetch origin` |  | 
| `git checkout --track origin/branch_name` | Check out a remote branch | 
| `git checkout -b [name_of_new_branch]` | Create a branch |
| `git push origin [name_of_new_branch]` | Push the branch to github |  
| `git branch -D origin/v2.6.1` | Delete a local branch | 
| `git branch -D <branch_name>` | Delete a local branch | 
| `git push origin --delete v2.6.2` | Delete remote branch |



## Tag

| Command | Description |
| --- | --- |
| `git tag` | List all of the tags in the branch |
| `git checkout -b <New Branch Name> <TAG Name>` | Create branch from tag |
| `git tag -a tag_name -m "message"` | Create  a tag | 
| `git push --follow-tags` | Push a tag | 
| `git tag -d <tag_name>`| Delete a local tag |
| `git push --delete origin <tagname>`| Delete a remote tag |


## Changes
| Command | Description |
| --- | --- |
| `git reset --hard` | Reset the changes |
| `git stash` | Temporarily park (stash) your uncommitted changes |
| `git stash pop` | Re-apply the changes parked using the stash command |
| `git pull` | Retrieve the changes |
| `git add .` | Add all of the files | 
| `git push` | PUsh your changes to remote repository|


