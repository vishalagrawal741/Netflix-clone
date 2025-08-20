# Git Commands for Netflix Clone

## First time setup (already done)
git init
git branch -M main
git remote add origin https://github.com/vishalagrawal741/Netflix-clone.git
git add .
git commit -m "first commit"
git push -u origin main

## Daily workflow (use these after making changes)
git add .
git commit -m "your message"
git push

## Fix line ending warning (already set once)
git config core.autocrlf true

## Check current status
git status

## If you want to see commit history
git log
