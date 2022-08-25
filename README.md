# Sample Java Application with no Instrumentation Code
This repository contains a simple Java application to calculate the nth number (between 1-90) in the Fibonacci sequence. It has no front end and runs locally in a terminal window. The built in load generator will generate and error every 4th attempt as it attempts to calculate a number outside of 1-90 on these attempts.


This application has not been instrumented. For an instrumented version of the same application, see the following repositories:

* [New Relic APM](https://github.com/Bijesse/fibonacci-java-apm)
* [OTel for New Relic](https://github.com/Bijesse/fibonacci-java-otel) 

## Requirements
* You must have a recent version of [Java](https://www.java.com/en/download/) and [Gradle](https://gradle.org/install/)  

## To run this application

1. From a new terminal window, clone this repository to your local machine using Git `git clone https://github.com/Bijesse/fibonacci-java-uninstrumented.git`

2. Navigate into your new workspace using cd `fibonacci-java-uninstrumented`

3. Build and run the app:
```shell
gradle bootRun
```
4. To generate traffic, open a new terminal window and run:
```shell
./load-generator.sh
```
