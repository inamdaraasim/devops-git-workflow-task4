# Git Commands Reference

## Repository

git init
git status
git add .
git commit -m "message"

## Branches

git branch
git switch main
git switch -c dev
git switch -c feature/documentation

## Remote

git remote -v
git push origin main
git pull origin main

## History

git log --oneline
git diff

## Tags

git tag
git tag -a v1.0.0 -m "First release"
git push origin --tags

## Stash

git stash
git stash list
git stash pop

## Ignore Files

.gitignore is used to exclude unnecessary
files from Git tracking.
