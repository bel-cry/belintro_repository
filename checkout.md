[<to the contents](./readme.md)

## git checkout

**git checkout *[file]*** - To start working in a different branch, use git checkout to switch branches.

Usage:

```bash=
# Checkout an existing branch
$ git checkout <branch_name>

# Checkout and create a new branch with that name
$ git checkout -b <new_branch>
```

In Practice:

```bash=
# Switching to branch 'new_feature'
$ git checkout new_feature
Switched to branch 'new_feature'

# Creating and switching to branch 'staging'
$ git checkout -b staging
Switched to a new branch 'staging'
```