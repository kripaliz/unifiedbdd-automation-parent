# UnifiedBDD Automation Parent

## BDD automation testing Made simple
[![Build Status](https://travis-ci.org/kripaliz/unifiedbdd-automation-parent.svg?branch=master)](https://travis-ci.org/kripaliz/unifiedbdd-automation-parent)

solution implemented in Java to support all plugins for automation execution using UnifiedBDD Automation Framework

* cucumber-jvm-parallel-plugin - generates test classes by splitting features into scenarios for parallel execution
* maven-surefire-plugin - executes the generated test classes of pattern defined in <include>**/Parallel*IT.java</include>
* allure-maven - generates allure reports from allure results

## Getting Started

UnifiedBDD requires the following to be installed

* [Java](http://www.oracle.com/technetwork/java/javase/downloads/index.html) 8 (at least version 1.8.0_112 or greater) 
* [Maven](https://maven.apache.org/download.cgi)
* [Eclipse](https://www.eclipse.org/downloads/)

### Eclipse

You can refer to this [nice blog post and video](https://www.joecolantonio.com/2017/03/23/rest-test-tool-karate-api-testing/) by Joe Colantonio which provides step by step instructions on how to get started using Eclipse.

* Follow instructions here: https://projectlombok.org/setup/eclipse for lombok setup
* Install eclipse plugins from the eclipse marketplace - YEdit, Natural (can just search for "cucumber")
* Follow instructions in the answer here: https://stackoverflow.com/questions/1886185/eclipse-and-windows-newlines to use Unix style line endings for new files