# Git_Course

## Code Notes
- git clone
- git status
- git add
- git commit -m "Message"
- git reset HEAD
- git branch
- git remote -v
- git push remoteName branchName
- git pull remoteName
- git init
- git remote add origin git@github.com:...
- git branch -M branchName
- git fetch origin
- git pull origin main
- git push -u remoteName branchName

## Git Configurations
- git config -l
- git help  config
- git config --global user.name []
- git config --global --unset {}
- git config --global --edit

## Public Key
- ssh-keygen -t rsa -b 4096 -C "email"
- ssh -T git@github.com

## Branching & Merging
- git branch branchName
- git checkout branchName
- git checkout -b branchName
- git branch -d branchName
- git branch -D branchName
- git branch -b newName
- git merge brancName

## Stashing
- git stash
- git stash pop
- git stash apply
- git stash list
- git stash save "message"
- git stash pop stash@{nember}
- git stash drop
- git stash drop stash@{number}
- git stash show
- git stash show stash@{number}
- git stash clear

## Restoring & Cleaning
- git restore --staged fileName
- git clean -n
- git clean -f