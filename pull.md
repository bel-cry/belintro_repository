[<to the contents](./readme.md)

## git pull

**git pull *[file]***- To get the latest version of a repository run git pull. This pulls the changes from the remote repository to the local computer.

Usage:

```bash=
$ git pull <branch_name> <remote_URL/remote_name>
```
in Practice:

```bash=
# Pull from named remote
$ git pull origin staging
From account_name.git.beanstalkapp.com:/account_name/repository_name
 * branch            staging    -> FETCH_HEAD
 * [new branch]      staging    -> origin/staging
Already up-to-date.

# Pull from URL (not frequently used)
$ git pull git@account_name.git.beanstalkapp.com:/acccount_name/repository_name.git staging
From account_name.git.beanstalkapp.com:/account_name/repository_name
 * branch            staging    -> FETCH_HEAD
 * [new branch]      staging    -> origin/staging
Already up-to-date.
```