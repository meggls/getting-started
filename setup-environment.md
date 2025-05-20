# Setup Environment

## Contents
- [Brew](#brew)
- [NPM](#npm)
- [Git](#git)
- [Zsh](#zsh)

## Brew
[Install Homebrew](https://brew.sh/)

## NPM

## Git & Github
Generate or locate existing SSH keys to be used for authentication
- [Check for existing SSH keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/checking-for-existing-ssh-keys)
- [Generate new SSH Key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

Check files

~/.gitconfig
```
[user]
	email = # insert email adress here
```

~/.ssh/config
```
Host github.com
  AddKeysToAgent yes
  UseKeychain yes
  IdentityFile ~/.ssh/id_rsa
```

Need to setup GitHub CLI auth as well
```
gh auth login
```

## Zsh
...coming soon

## Misc Apps
Some helpful apps
- VSCode
- Sublime
- Insomnia