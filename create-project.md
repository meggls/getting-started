# Create a Project

## Contents


## Create a New Project Directory

    PROJECT=getting-started

    cd ~/Documents/git

    mkdir $PROJECT
    cd $PROJECT

## Add Project to Git

Initialize a git repo locally
```
USER=meggls
PROJECT=getting-started

git init
git add .
git commit -am 'init commit'
git remote add origin git@github.com:$USER/$PROJECT.git
gh repo create $PROJECT --public --source=. --remote=upstream
git push -u origin master
```