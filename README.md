# Git commands
## Git status
To check if there have been any changes made use the following command:

```
git status
```
## Git add
To add files to git use either:

```
git add filename.fileextension
```

or add all tracked files which have been modified since the last commit
```
git add -u
```
or all files in the directory

```
git add .
```
## Git commit

```
git commit -m 'Comment regarding commit'
```

## .gitignore

Files which are ignored by git, if they are in the gitignore file for example if we the following text in .gitignore:

```
/dir2
log.txt
.*pdf
```

Then the files in the /dir2 folder are ignored along with the log.txt file and all pdf documents

## Git branch relate

Create branch

```
git branch branchname
```

Switch to specific branch

```
git checkout branchname
```

Create and switch to that branch in one command by using
```
git checkout -b branchname
```


## Git Merge
```
git merge branchname
```

## Git Remote
```
git remote add origin url
```

```
git push -u origin master
```

## Git Workspace
Rather than cloning a repo to work on a separate branch at the same time (e.g. for running tests on a PR), one can use git worktree, which shares resources between the worktrees.

```
git worktree add ../worktree-dir branch```
```

## TODO
git switch
git checkout --theirs path





