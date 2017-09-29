# oiosaml2

This is a fork from oiosaml2 for Java. 


The principal reason to make this fork is change the loggin systen for slf4j.


[Home Page of Fork](https://digitaliser.dk/group/42063/resources)


[Fork from subversion](https://svn.softwareborsen.dk/oiosaml.java/oiosaml2/)



OIOSAML.java is distributed under the Mozilla Public License 1.1, and is based on OpenSAML 2.0, which is released under the Apache License 2.0.

See **docs/index.html** for full documentation, including installation instructions.


This project is build with maven:

**Main phases**
* clean — delete target directory
* validate — validate, if the project is correct
* compile — compile source code, classes stored in target/classes
* test — run tests
* package — take the compiled code and package it in its distributable format, e.g. JAR, WAR
* verify — run any checks to verify the package is valid and meets quality criteria
* install — install the package into the local repository deploy — copies the  nal package to the remote repository

**Useful command line options**

* **-DskipTests=true** compiles the tests, but skips running them
* **-Dmaven.test.skip=true** skips compiling the tests and does not run them


```sh
mvn clean package 
```
