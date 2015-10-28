# README #

Steps to run this project:

1. Import this project as Gradle project in your IDE.
2. In terminal window of your IDE, run following commands:
    gradle build
    gradle run

Note: You should have gradle package installed in your system in order to import this project.

### Project Summary ###

This is a college assignment where we had to implement RestFUL web services using Spring MVC framework.

* There are two Model classes : Poll and Moderator. The Poll class holds the data structure of all the polls available for users.
* The Moderator class holds the user data structure who will do the polling/voting using RestFUL web services resources.
* Version - 0.1.0
* 'api' directory holds the class of RestFul web service controller and basic header authorization.

### Additional Changes ###
* Kafka Email Notification
* Spring Scheduler for scheduling email notification.
* MongoDb to persist data of Polls and Users.
* Advanced Header Authorization.

### Setup Information ###

* build.gradle file is already included in this project to resolve all the dependency.
* After building the project, it will create a jar file with name 'myvote' with version number as 0.1.0

### Who do I talk to? ###

* You need to talk to repo owner for further details.