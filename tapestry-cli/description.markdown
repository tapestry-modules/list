---
title: Tapestry 5 Command Line Interpreter (tapestry5-cli)
---

# Tapestry 5 Command Line Interpreter

Tapestry5-cli can be used to parse the command line, validate the provided values, and eventually access
options and inputs via specific service, similar to what is currently done with `Symbols`.

Tapestry5-cli leverages Apache commons-CLI for parsing the command line,
a simplified version of tapestry-beanvalidator for validating the inputs, and
tapestry-IoC for collecting distributed configuration and setting up the all the rest.

Tapestry5-cli is mainly designed for non-web applications that are based on tapestry-ioc.

## Source code

Source code is available on GitHub at: [tapestry5-cli source](https://github.com/alessiogambi/tapestry5-cli)

### Snapshots

Maven Artifact:  

	<groupId>org.gambi</groupId>
	<artifactId>tapestry5-cli</artifactId>
	<version>0.1-SNAPSHOT</version>

From the Repository:

	<repository>
		<name>Infosys Repo</name>
		<id>infosys-repo</id>
		<url>http://www.infosys.tuwien.ac.at/mvn</url>
	</repository>

### Releases

There are not stable released yet.

### Contributors

* Alessio Gambi

### Advisory Board

* Thiago H de Paula Figueiredo (Tapestry Committer)  
* Barry Books 
