# Java / Gradle / Docker

An example Gradle project to build a Java EE EAR. This project is based on sample
code by Danny Coward from "Java EE 7: The Big Picture", Oracle Press, 2015.

Example application has been enhanced with gradle wrapper for standardizes a project experience on a given Gradle version, leading to more reliable and robust builds.

Application is alos dockerized levraging the gradle plugins to perform the docker builds and deplyments to local enviroment. This creates seamles development experiance where the develoer updates the code then runs a suit of commands wich lead to consistnat and reproducable CI experience.

There are some updates in the future that will:
- Allow the developer to configure the Java EE application / docker deplymnet details from `gradle.properties`
- Integrate minikube deployment into the gradle targets.
