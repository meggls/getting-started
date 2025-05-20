# Getting Started

## Setup Environment

### Brew
[Install Homebrew](https://brew.sh/)

### NPM

### Git
Generate or locate existing SSH keys to be used for authentication
- [Check for existing SSH keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/checking-for-existing-ssh-keys)
- [Generate new SSH Key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)



Add 
~/.ssh/config
```
Host github.com
  AddKeysToAgent yes
  UseKeychain yes
  IdentityFile ~/.ssh/id_rsa
```

## Create New Project

    PROJECT_DIR=getting-started

    cd ~/Documents/git

    mkdir $PROJECT_DIR
    cd $PROJECT_DIR

## Add Project to Git
Initialize a git repo locally

    PROJECT_DIR=getting-started

    git init
    git add .
    git commit -am 'init commit'
    git remote add origin git@github.com:meggls/$PROJECT_DIR.git
    git push --set-upstream $PROJECT_DIR master
    git push $PROJECT_DIR

