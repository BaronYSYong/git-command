# Git

## Reference
* [Change remote url](https://help.github.com/en/articles/changing-a-remotes-url)

## Command
* git cherry-pick -e -m 1 {commit_ref_number}

* rename a branch
```
# Rename the local branch to the new name
git branch -m <old_name> <new_name>

# Delete the old branch on remote - where <remote> is, for example, origin
git push <remote> --delete old_name

# Push the new branch to remote
git push <remote> new_name

# Reset the upstream branch for the new_name local branch
git push <remote> -u new-name
```
* drop the unnecesarry commit
```
$ git rebase -i HEAD~4
```
