# SpringBootStartupIssue
Demo proving Spring Boot Issue

This little demo app is created to showcase the spring boot issue that I am having.

Steps to reproduce:

1. mvn clean package
2. create a config directory at the same level with the produced demo-0.0.1-SNAPSHOT.jar file and copy the src/main/resources/application.yml file in it.
3. java -jar demo-0.0.1-SNAPSHOT.jar

Application will simply not start without displaying any error.

Spring Boot Version:1.5.8

OS Version:Ubuntu 3.13.0-24-generic
