# Run xampp
    sudo ./xampp-linux-x64-8.2.12-0-installer.run
# Install waamp
    sudo apt update
    sudo apt install apache2
    sudo apt update
    sudo apt install mysql-server
    sudo apt install php libapache2-mod-php php-mysql
    sudo apt install phpmyadmin
    sudo systemctl restart apache2




# WhatsApp
    sudo apt update
    sudo snap install whatsapp-for-linux
# Unistall Java
    java -version
    sudo apt remove openjdk-21-jdk
    sudo rm -rf /usr/lib/jvm/*
    sudo apt update

# Java
    sudo apt update
    java -version
    java -version


# tree
    sudo apt update
    sudo apt install tree
    tree
Run this command in terminal to install tree.
# MongoDB

    https://www.youtube.com/watch?v=HSIh8UswVVY

Follow this vidoe link to install MongoDB in Ubuntu.

# Android

    https://www.youtube.com/watch?v=xMCAkUsdDT8&list=PLjVLYmrlmjGdDps6HAwOOVoAtBPAgIOXL&index=7
Follow this Video link to install Android in Ubuntu.

# Postman
    https://www.youtube.com/watch?v=XBxtX-tWBr4&ab_channel=ProgrammingKnowledge2
Youtube link to install Postman in Ubuntu.
# Command to Install Postman
    sudo snap install postman
# Chrome
    sudo apt install ./google-chrome-stable_current_amd64.deb
Download Chrome ,Open terminal, go to Downloads directory and run this command.
# Unistall Chrome
    sudo apt-get remove google-chrome-stable

# Microsoft Edge
    sudo apt install ./microsoft-edge-stable_121.0.2277.128-1_amd64.dev
Download Microsoft Edge, Open terminal, go to Downloads directory and run this command according to your downloded version.
# Unistall Microsoft Edge
    dpkg --get-selections | grep microsoft-edge
    sudo apt remove microsoft-edge-stable
    sudo apt purge microsoft-edge-stable
# pug

    sudo apt update
    sudo apt install nodejs npm
    sudo npm install -g pug-cli
    pug --version
Follow this command in terminal of Ubuntu to install pug.
# Apache
    sudo apt update
    sudo apt install apache2
    sudo ufw app list
    sudo ufw allow 'Apache'
    sudo ufw status
    sudo systemctl status apache2
# Unistall Apache
    sudo systemctl stop apache2
    sudo apt purge apache2
    sudo apt autoremove
