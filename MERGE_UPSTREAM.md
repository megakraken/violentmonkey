### Merge latest upstream changes

``` sh
# Add upstream remote to local repository
$ git remote add upstream https://github.com/violentmonkey/violentmonkey.git

# Fetch latest upstream changes
$ git fetch upstream

# Switch to main branch
$ git checkout master

# Merge upstream into fork
$ git merge upstream/master

# Resolve merge conflicts in the listed files
# via TortoiseGit + WinMerge or on command line with
$ git add <affected_files>
$ git commit

# Push updated master to fork
$ git push origin master
```
