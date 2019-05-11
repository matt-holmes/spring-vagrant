# Spring Vagrant
---
## Prerequisite
1. install vagrant - https://www.vagrantup.com/

## Setup (time 10mins):
1. git clone https://github.com/matt-holmes/spring-vagrant.git
2. cd spring-vagrant
3. vagrant up
4. vagrant ssh

### Install additional packages:
1. sudo add-apt-repository ppa:linuxuprising/java
2. sudo apt-get update
3. sudo apt-get install oracle-java11-set-default -y
4. sudo apt-get install unzip -y
5. curl -O https://downloads.gradle.org/distributions/gradle-5.4.1-bin.zip
6. sudo mkdir /opt/gradle/
7. sudo unzip -d /opt/gradle/ gradle-5.4.1-bin.zip
8. export PATH=$PATH:/opt/gradle/gradle-5.4.1/bin

### Optional packages:
1. sudo apt-get install mysql-server -y
2. sudo apt-get install git -y

## Verify packages:
* gradle -v
        
        ------------------------------------------------------------
        Gradle 5.4.1
        ------------------------------------------------------------

        Build time:   2019-04-26 08:14:42 UTC
        Revision:     261d171646b36a6a28d5a19a69676cd098a4c19d

        Kotlin:       1.3.21
        Groovy:       2.5.4
        Ant:          Apache Ant(TM) version 1.9.13 compiled on July 10 2018
        JVM:          11.0.2 (Oracle Corporation 11.0.2+9-LTS)
        OS:           Linux 3.13.0-158-generic amd64

    
    
* java --version

        java 11.0.2 2019-01-15 LTS
        Java(TM) SE Runtime Environment 18.9 (build 11.0.2+9-LTS)
        Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.2+9-LTS, mixed mode)


