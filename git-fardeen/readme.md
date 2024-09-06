## git hidden folder
there is a hidden folder called `.git` which tells you that your project is a git repo.


if we want to create a git repo in a new project we create the folder and initialize that repo using `git init`
```
git init
```

```
mkdir /workspaces/tmp/newproject
cd /workspaces/tmp/newproject
git init
touch readme.md
code readme.md
git status
#make changes to readme.md
git commit -a -m "add description"
```
## cloning 
we can clone in three ways: https, ssh and github CLI
### https 
```md
git clone https://github.com/fbholai/Github-Examples.git
```

## commits

## branches

## remotes

## stashing 

## merging