# Git Hands-on 4 - Merge Conflict Resolution

## Objective
Learn how to resolve merge conflicts in Git.

## Commands Used

git branch GitWork
git checkout GitWork
git add hello.xml
git commit
git checkout master
git merge GitWork
git add hello.xml
git commit
git branch -d GitWork
git log --oneline --graph --decorate --all