# Sprint Vagrant
---
## Setup:
git clone https://github.com/matt-holmes/spring-vagrant.git
cd spring-vagrant
vagrant up
vagrant ssh

## Install additional packages
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer -y
sudo apt-get install mysql-server -y
sudo apt-get install git -y
curl -O https://downloads.gradle.org/distributions/gradle-3.2.1-bin.zip
sudo mkdir /opt/gradle/
sudo unzip -d /opt/gradle/ gradle-3.2.1-bin.zip
export PATH=$PATH:/opt/gradle/gradle-3.2.1/bin
