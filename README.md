# java-web-api-bloop-sbt-spring-micrometer-hello

## Description
Another way to serve web content.
Uses micrometer to expose endpoints
through springframework actuator.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- java
- bloop-sbt

## Docker stack
- openjdk:8-jdk-alpine

## To run
`sudo ./install.sh -u`
- Available http://localhost/actuator

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://github.com/monodot/spring-boot-with-metrics/blob/main/pom.xml
