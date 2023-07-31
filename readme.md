# Git Tutorial

## See Git version
- git --version 

## git config
## config username
- git config --global user.name "username"
## config email
- git config --global user.email "email"
## configurar editor
- git config --global core.editor "code --wait"
## set config
- git config --global -e
## set config multiple OS
- git config --global core.autocrlf input

## bash basic commands
## list dir
- ls
## power dir
- pwd
## change directory
- cd
## remove file
- rm "file"
## move file
- mv "file" "directory"
## view content file
- cat "file"

## git
## git init
- git init
## list dir hide
- ls -a

## git view status
- git status
## git add files
- git add <option>
## git add specifict file
- git add filename.txt
## git add all
- gid add .

## git commit
- git commit -m "comment"
## git remove file
- git rm "file"
## git restore
- git restore --staged "file"
## git discart changes
- git restore "file"

## git ignore file
- .gitignore > "env" ".node_modules"
## git show diferences
- git diff
## git show diferences un stage
- git diff --stage
## git view history
- git log
## exit of this screen
- press "Q"
## git view history in oneline
- git log --oneline

## git view branch
- git branch
## git create and change branch
- git checkout -b branch_name
## git change branch
- git checkout branch_name
## git bring the change to the branch
- git merge branch_name

## git add to github
- git remote add origin LINK
- git push -u origin master