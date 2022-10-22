#!/usr/bin/bash
termux-setup-storage
pkg update
pkg upgrade -y
pkg dist-upgrade -y
pkg install root-repo -y
pkg install x11-repo -y
pkg install termux-api -y
pkg install git -y
pkg install wget -y
pkg install curl -y
pkg install python -y
pkg install php -y
pkg install ruby -y
pkg install mc -y
pkg install zsh -y
pkg install toilet -y
pkg install figlet -y
pkg install cloudflared -y
pkg install openssh -y
pkg install sshpass -y
gem install lolcat
python3 -m pip install --upgrade pip
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"





















