# Git Commands

### git status
to check the status of the repo

### git add <file> | *
git add <file> or git add *
adds the changes to the staging area

### git restore --staged <file>
to unstage added file

### git restore <file>
to rollback changes of a file

### git commit
commits the changes to the local repo

### git commit -a -m "commit add"
add and commit

### git branch
lists all the branches on the local repo

### git remote -v
lists the remote origin

### git push <origin> <branch>
ex. git push origin master
pushes commits to the remote repo

### git pull origin
pulls changes from the remote, it is fetch and merge

### git config -l
lists configurations

### git help config
open config docs

### git config --global user.email
get config value

### git config --global user.email "mali@gmail.com"
set config value

### git init
creates empty repo

### git config --global alias.st status
create alias for a command

### git branch
list all branches

### git branch <branch name>
creates new branch

### git checkout <branch name>
checkout branch

### git branch -d <branch>
delete branch

### git merge <branch name>
merges branch in a branch

### git stash
saves added files out of staging area

### git stash list
lists the stash

### git stash pop
unstash and deletes the stash box

### git stash save "save message"
stashes with save message

### git stash apply
unstaches the changes only and keep the files in the stash

### git stash pop stash@{<id>}
unstash specific stash

### git stash drop
drops stash

### git stash show
shows the stash content

### git stash clear
clears the stashes





