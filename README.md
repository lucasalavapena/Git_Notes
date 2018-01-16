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

or add all files which have been modified since

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

## Git branch

Create branch

```
git branch branchname
```

Switch to specific branch

```
git checkout branchname
```

## Touch

Create file using unix command

```
touch name.fileextension
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

