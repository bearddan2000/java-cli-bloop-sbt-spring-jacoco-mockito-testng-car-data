# java-cli-bloop-sbt-spring-jacoco-mockito-testng-car-data

## Description
A POC for bloop-sbt app using testng.
mockito, and jacoco. Writes test
results to console and html.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- java
- bloop-sbt
  - testng
  - jacoco
  - spring
  - mockito

## Docker stack
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Listener code](https://livebook.manning.com/book/bloop-sbt-in-action/chapter-5)
- [Build code concept](https://github.com/bloop-sbt/junit-interface/blob/develop/src/sbt-test/simple/test-listener/build.sbt)
