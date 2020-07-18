## Basic
* sudo apt-get update
* sudo apt-get upgrade
* sudo apt-get install software-properties-common apt-transport-https wget

## Chrome
* wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
* sudo dpkg -i google-chrome-stable_current_amd64.deb
* rm google-chrome-stable_current_amd64.deb

## Slack
* wget https://downloads.slack-edge.com/linux_releases/slack-desktop-4.0.2-amd64.deb
* sudo dpkg -i slack-desktop-4.0.2-amd64.deb
* rm slack-desktop-4.0.2-amd64.deb

## Visual Studio Code
* wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
* sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
* sudo apt-get update
* sudo apt-get install code

## Git
* sudo apt-get install git
* Create a new identity file with the command : `ssh-keygen` in `~/.ssh` folder
* add config file in ~/.ssh/config
```
Host github.com
User <github username>
Hostname github.com
PreferredAuthentications publickey
IdentityFile ~/.ssh/<filename>
```

## OpenVPN
* sudo apt-get install openvpn

## Zoom 
* https://www.zoom.us/download

## MySQL workbench 
* sudo apt-get install mysql-workbench

## Snap package manager
* sudo apt-get install snap

## Nods JS and NPM 
* sudo snap install node --channel=12/stable --classic

## NVM 
* wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
* nvm install 12
* nvm install 8
