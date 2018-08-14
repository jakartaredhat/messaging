# Eclipse Project for JMS

This repository contains the API definition source code for the JMS API. This is used  to generate the official Javadocs.

__However it is not used to directly generate the JMS API jar published in Maven Central.__ Instead, when a new version of the JMS specification is released, the API classes are copied to [Open Message Queue](https://projects.eclipse.org/projects/ee4j.openmq) and the JMS API jar built from there.    

Web-site details are TBD

This project uses `maven` as build tool, sources follows maven project structure.


## Build from Source

Navigate to the directory and Type `mvn clean package` to produce java api jar file. `mvn javadoc:jar` will produce java doc jar file.
