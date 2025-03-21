##  initializing a repository
git init

## status of staging area
git status 
git status -s

## add files to staging area
git add (filename.extention/ *.extension / .)

## comiting files to repository 
git commit -m "commit message"

## stage and comit in one go
git commit -am "comit message"

## remove files 
git rm  filname.extention

## rename or move file
git mv oldname.extention newname.extention

## to ignore certain files and folders
.gitignore

## viewing the staged changes
git diff --staged

## viewing unstaged chnages
git diff

## view history 
git log
git log --online
git log --online --reverse

## view a commit 
git show [commit id / HEAD / HEAD~2]: {path to file}
git ls-tree [commit id / HEAD / HEAD~2]: {path to file}

