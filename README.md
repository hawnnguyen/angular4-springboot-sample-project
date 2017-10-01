# README.md

angular4-springboot-sample-project 
Demonstrates usage of Angular CLI how to integrate it into springboot.

## Prerequisite
You must have the following setups to proceed:

1. Setup for Node.js and Npm installed. 
	Please see (http://angular.io) to Setup your local Development Enviiornment
2. JDK 1.8
3. Maven Installed 3.2 or higher (https://maven.apache.org)

## Building Angular

The projects are loosely coupled so you can just run and build the Angular CLI without the Springboot project.  Please go into the herios-digital-product folder for further instructions  

## Building Angular CLI and SpringBoot

The springboot project has the plugins configured to trigger the Angular CLI build and integrates into the SpringBoot application (please see the pom.xml for more info under "heros-angular-springboot").  

After you git clone this repo please perform the following:

```linux
cd heros-angular-springboot
mvn clean install
mvn spring-boot:run
```

## Fire it Up!

http://localhost:8080/

## Reference
For more information please see

http://javasampleapproach.com/java-integration/integrate-angular-4-springboot-web-app-springtoolsuite

