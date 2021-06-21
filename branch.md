[<to the contents](./readme.md)

## git branch

**git branch *[file]***- To determine what branch the local repository is on, add a new branch, or delete a branch.

Usage:

```bash=
# Create a new branch
$ git branch <branch_name>

# List all remote or local branches
$ git branch -a

# Delete a branch
$ git branch -d <branch_name>
```

In Practice:

```bash=
# Create a new branch
$ git branch new_feature

# List branches
$ git branch -a
* SecretTesting
  new_feature
  remotes/origin/stable
  remotes/origin/staging
  remotes/origin/master -> origin/SecretTesting
  
# Delete a branch
$ git branch -d new_feature
Deleted branch new_feature (was 0254c3d).
```