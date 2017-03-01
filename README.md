# Sprint Vagrant
---
## Setup:
1. git clone https://github.com/matt-holmes/spring-vagrant.git
2. cd spring-vagrant
3. vagrant up
4. vagrant ssh

## Install additional packages:
1. sudo add-apt-repository ppa:webupd8team/java
2. sudo apt-get update
3. sudo apt-get install oracle-java8-installer -y
4. sudo apt-get install mysql-server -y
5. sudo apt-get install git -y
6. sudo apt-get install unzip -y
7. curl -O https://downloads.gradle.org/distributions/gradle-3.2.1-bin.zip
8. sudo mkdir /opt/gradle/
9. sudo unzip -d /opt/gradle/ gradle-3.2.1-bin.zip
10. export PATH=$PATH:/opt/gradle/gradle-3.2.1/bin


##Check packages:
* gradle -v
        ------------------------------------------------------------
        Gradle 3.2.1
        ------------------------------------------------------------

        Build time:   2016-11-22 15:19:54 UTC
        Revision:     83b485b914fd4f335ad0e66af9d14aad458d2cc5

        Groovy:       2.4.7
        Ant:          Apache Ant(TM) version 1.9.6 compiled on June 29 2015
        JVM:          1.8.0_121 (Oracle Corporation 25.121-b13)
        OS:           Linux 3.13.0-85-generic amd64
    
* java -version
    java version "1.8.0_121"
    Java(TM) SE Runtime Environment (build 1.8.0_121-b13)
    Java HotSpot(TM) 64-Bit Server VM (build 25.121-b13, mixed mode)
