# To Install Al Quran
    https://flathub.org/apps/org.gtaf.quran
Go to this link and download. Run the below command in terminal in the downloaded directory to install.
```
sudo apt install flatpak
flatpak install flathub org.gtaf.quran
```
Run this directory to run this App on own directory.
````
flatpak run org.gtaf.quran
````
# To Install Flutter
    https://www.youtube.com/watch?v=e63OlW_2gpQ&ab_channel=CodeWithArjun

# Mysql Workbench
    sudo snap install mysql-workbench-community


# WineHQ
    sudo dpkg --add-architecture i386 
    sudo mkdir -pm755 /etc/apt/keyrings
    sudo wget -O /etc/apt/keyrings/winehq-archive.key https://dl.winehq.org/wine-builds/winehq.key
    sudo wget -NP /etc/apt/sources.list.d/ https://dl.winehq.org/wine-builds/ubuntu/dists/jammy/winehq-jammy.sources
    sudo apt update
    sudo apt install --install-recommends winehq-stable



# Arduino
    sudo apt update
    sudo snap install arduino

Download Arduino and click arduino-ide

# Unistall Arduino
    sudo apt-get remove arduino
    sudo apt-get purge arduino
    dpkg --get-selections | grep arduino


# Install Apache Tomcat
    java -version
    sudo apt-get update
    sudo apt-get install default-jdk
    sudo update-java-alternatives -l
After run this command download tomcate and extract that file.
 ```
code ./bashrc
```
Go to VS Code and save CATALINA_HOME and JAVA_HOME path.<br>
To cheak :

```
echo $CATALINA_HOME
echo $JAVA_HOME
```
Save this file in conf/tomcat-users.xml between &lt;tomcat-users>&lt;/tomcat-users>:
```
<!-- user manager can access only manager section -->
<role rolename="manager-gui" />
<user username="manager" password="_add_password" roles="manager-gui" />
<!-- user admin can access manager and admin section both -->
<role rolename="admin-gui" />
<user username="admin" password="_add_password_" roles="manager-gui,admin-gui" />
```
Finaly run this command and go to localhost:8080 in your browser:
```
chmod +x bin/startup.sh
./bin/startup.sh
```
# Eclipse
    sudo apt update
    sudo apt install default-jdk
    wget https://mirror.umd.edu/eclipse/oomph/products/latest/eclipse-inst-jre-linux64.tar.gz
    tar -xvf eclipse-inst-jre-linux64.tar.gz
    cd eclipse-installer/
    ./eclipse-inst
    
    
https://linux.how2shout.com/2-methods-to-install-eclipse-ide-on-ubuntu-22-04-or-20-04-lts/    //follow this link

# Flatter
    sudo apt update
    sudo apt install python3-pip
    pip3 install flatter
    import flatter
    pip3 show flatter


# Dart
    sudo apt update
    sudo apt install apt-transport-https gnupg
    sudo sh -c 'wget -qO- https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add -'
    sudo sh -c 'wget -qO- https://storage.googleapis.com/download.dartlang.org/linux/debian/dart_stable.list > /etc/apt/sources.list.d/dart_stable.list'
    sudo apt update
    sudo apt install dart
    dart --version


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
# Batter
#### Install
    git clone https://github.com/AdnanHodzic/auto-cpufreq.git
    cd auto-cpufreq && sudo ./auto-cpufreq-installer
    sudo auto-cpufreq --install
    
#### To check version and status
    auto-cpufreq --version
    sudo systemctl status auto-cpufreq
    sudo auto-cpufreq --stats
    sudo auto-cpufreq --install

#### To stop
    sudo systemctl stop auto-cpufreq


    
