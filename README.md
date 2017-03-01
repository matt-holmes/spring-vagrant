# Sprint Vagrant
---
## Setup:
1. git clone https://github.com/matt-holmes/spring-vagrant.git
2. cd spring-vagrant
3. vagrant up
4. vagrant ssh

## Install additional packages
1. sudo add-apt-repository ppa:webupd8team/java
2. sudo apt-get update
3. sudo apt-get install oracle-java8-installer -y
4. sudo apt-get install mysql-server -y
5. sudo apt-get install git -y
6. curl -O https://downloads.gradle.org/distributions/gradle-3.2.1-bin.zip
7. sudo mkdir /opt/gradle/
8. sudo unzip -d /opt/gradle/ gradle-3.2.1-bin.zip
9. export PATH=$PATH:/opt/gradle/gradle-3.2.1/bin
