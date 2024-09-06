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
git status (shows you which files are will or will not be commited)
git add . (add all tracked files)
git add readme.md (track an individual file with the name readme.md)
git reset (makes the tracked files untracked for undoing changes)
git config --global core.editor emacs (Sets a global editor)
git config --list --show-origin (shows where the gitconfig file is located, this file stores your global configurations for git such as mail, username)
git config --global user.name "test"
git config --global user.email ssd@sdsd.com
#make changes to readme.md
git commit -a -m "add description" (-a tells git to automatically stage files that have been modified)
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

## add
when we want to stage changes that will be included in the commit we can use the . to add all the files

## reset
reset allows you to remove staged files staged changes to unstaged changes


## stash
You can use stashing for putting your work aside before making a commit

to create a stash: git stash
to show the stashes: git stash list
