# Git Hands-on 3 - Branching and Merging

## Objective
Learn how to create a branch, commit changes in the branch, merge it into the master branch, and delete the branch.

## Branch Created
GitNewBranch

## Commands Used
git branch GitNewBranch
git checkout GitNewBranch
git add branchfile.txt
git commit -m "Added branchfile in GitNewBranch"
git checkout master
git diff master GitNewBranch
git merge GitNewBranch
git log --oneline --graph --decorate
git branch -d GitNewBranch
git status