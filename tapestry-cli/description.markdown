---
title: Tapestry 5 Command Line Interpreter (tapestry5-cli)
---

# Tapestry 5 Command Line Interpreter

Tapestry5-cli can be used to parse the command line as specified by the user, validate the provided values, and eventually export options and other inputs via the command line as Symbols.

Tapestry5-cli leverages Apache commons-CLI for parsing the command line, tapestry-beanvalidator for validating the inputs, tapestry-IoC for collecting distributed configuration and setting up the all the rest.

This library is exported as plain tapestry-library, and is designed for non-Web applications that are based on Tapestry-IoC (but not Tapestry-Core!).


## Source code

[tapestry5-cli source](https://github.com/alessiogambi/tapestry5-cli)

## Jars

http://www.infosys.tuwien.ac.at/mvn

### Snapshots

Artifact:

	<groupId>org.gambi</groupId>
	<artifactId>tapestry5-cli</artifactId>
	<version>0.0.1-SNAPSHOT</version>

### Releases

There are no released versions yet.

### Contributors

* Alessio Gambi

### Advisory Board

* Thiago H de Paula Figueiredo (Tapestry Committer)  
* Barry Books 
