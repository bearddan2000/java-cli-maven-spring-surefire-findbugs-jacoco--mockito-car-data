# java-cli-maven-spring-surefire-findbugs-jacoco--mockito-car-data

## Description
Analyze source code for potential bugs.
A POC for spring app. Testing done with surefire
and jacoco plugins using mockito framework.

## Tech stack
- java
- maven
	- findbugs
  - spring
  - surefire
  - jacoco
  - mockito
    - junit5

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/junit-5)
- [Jacoco config](https://www.baeldung.com/jacoco)
