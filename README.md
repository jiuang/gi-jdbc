# gi-jdbc
[![Build Status](https://travis-ci.org/p6spy/p6spy.svg?branch=master)](https://travis-ci.org/p6spy/p6spy)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/p6spy/p6spy/badge.svg)](https://maven-badges.herokuapp.com/maven-central/p6spy/p6spy) 
[![Bintray](https://api.bintray.com/packages/p6spy/maven/p6spy%3Ap6spy/images/download.svg) ](https://bintray.com/p6spy/maven/p6spy%3Ap6spy/_latestVersion)

# Introduction
* gi-jdbc (gannalyo intercept jdbc) is a light weight and powerful application for intercepting JDBC operations.
* Reference the [P6Spy](https://github.com/p6spy/p6spy) project.


# Functions
* To intercept JDBC operations.
* To do something around JDBC operations. 


# Purpose
* To hope that can give help to some developers who want to do something around JDBC operations.


# Instruction
* a. To import this project or jar file to your application.
* b. To build path 'resources\META-INF\services' if it not exists.
* c. To create text file which is named for 'com.gannalyo.sqlinterceptor.listener.JdbcEventListener' in above path.
* d. To create java file which must extend 'com.gannalyo.sqlinterceptor.listener.JdbcEventListener' and override all methods in your application.
* e. To copy the name of java file, include package name and class name, and to paste it in the text file.
* f. To code your code in some methods of the java file.


# Thanks for [P6Spy](https://github.com/p6spy/p6spy) team very much!


# Contact us
* e-mail: javajob126email@gmail.com, javajob126email@126.com
* wechat: gannalyo
