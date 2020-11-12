## git flow failed init from a cloned repo

git flow fails sometimes when cloning a repository and trying to initialize.
See https://github.com/nvie/gitflow/issues/121

Here is a workaround:

```bash
$ git checkout master
$ git checkout develop
$ git branch -a
* develop
  master
  remotes/origin/HEAD -> origin/develop
  remotes/origin/develop
  remotes/origin/master
$ git init
```

## Rebase & merging conflicts example

```bash
# Look at conflict:
$ git log --graph --oneline --all

# Fetch remote (you can see it in the graph)
$ git fetch upstream

# Rebase
$ git rebase origin/hotfix/v0.13.5

# If there is a change you don't want, make sure your HEAD is pointing to your latest commit and do:
$ git reset --hard HEAD

# Then, rebase
```
Some documentation:
- https://stackoverflow.com/questions/23517464/error-cannot-pull-with-rebase-you-have-unstaged-changes
- https://devconnected.com/how-to-git-reset-to-head

