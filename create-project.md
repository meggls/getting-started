# Create New Project

    PROJECT_DIR=getting-started

    cd ~/Documents/git

    mkdir $PROJECT_DIR
    cd $PROJECT_DIR

# Add Project to Git

Initialize a git repo locally

    PROJECT_DIR=getting-started

    git init
    git add .
    git commit -am 'init commit'
    git remote add origin git@github.com:meggls/$PROJECT_DIR.git
    git push -u origin master

