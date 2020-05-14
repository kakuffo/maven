
# Maven Overview

Maven a tool developed by Apache to support their software development project initially released on 13 July 2004.  
Maven allows for software project management, and software project reporting by providing an overview and visualization 
of the project.  Maven, often known technically as mvn is open source and license as Apache License 2.0.  I view the 
tool as one of the earliest tools that reconciled Java development software project activity automation into a single 
framework.  The use of Extensible Markup Language ( XML ), made its adoption in the software development world rapid, 
and championed by XML connoisseurs.  
Maven affords development teams the ability to continuously apply automation to 
key phase in a Java software development lifecycle.  Uniformity, and consistency in the development phase after coding 
is vital for overall quality control in any size of software development team.  

The phases involved in producing software are; managing the development configuration and dependency artifacts 
configuration installation, and management; the unit testing of software artifact; the compiling of the software artifact,
the packaging of unit tested software artifacts, the packaging of software unit artifacts into software components, integration
testing of the software package, integration of the software components, packaging of production-ready software into 
release candidates; acceptance test of the realise candidate software, package of the release software.

Automation is realised in Maven by the extensibility afforded by XML, and through plugins, goals, dependencies.  The
definitions of plugins, goals, and dependencies in an XML file known as a POM (Project Object Module) file.
The Maven POM are of a xml design patterns called venetian blind affording maven the advantage of defining plugins, goals, 
and dependencies global type definitions to increase reuse capabilities necessary for automation.
 
The project development configurations are defined in another XML file vital to Maven, and called the Settings.xml file.
There are two locations where a settings.xml file may live:

* The Maven install: 

`` xml
${maven.home}/conf/settings.xml
``
* A user’s install: 

`` jave
${user.home}/.m2/settings.xml
 ``

![Image](https://github.com/kakuffo/maven/blob/master/images/Maven-Architecture-ju.png)

 Download Link to Maven
 

## What is Maven

Maven is an Apache open source software for automating software project processes.  Maven is deployed
to manage;

* Software project configuration management.
* Software project artifacts management.
* Software project artifact dependencies management.
* Software project artifacts initialisation.
* Software project artifacts compiling.
* Software project artifacts packaging.
* Software project artifacts unite/integration/acceptance testing.
* Software project package deployment.
* Software project package documentation.
* Software project status reporting.
* Software project artifacts cleaning.

### Maven Objectives



### Maven Architecture


#### Maven configuration management


#### Configuring your Local Repository

#### Configurring Proxy


#### Configuring Parallel Artifact Resolutio


