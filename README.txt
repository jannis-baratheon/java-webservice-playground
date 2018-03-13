Note
====

A callback WS example extracted from the [Apache CXF repository](/apache/cxf). [Maven-wrapper](/takari/maven-wrapper) has also been thrown in for developer convenience.

Below is the original README from the example.

Callback Demo
=============

This demo shows a client creating a callback object by 
passing an EndpointReferenceType to the server. The 
EndpointReferenceType is then used by the server to call 
back on the callback object.

Please review the README in the samples directory before
continuing.


Prerequisite
------------

If your environment already includes cxf-manifest.jar on the
CLASSPATH, and the JDK and ant bin directories on the PATH
it is not necessary to set the environment as described in
the samples directory's README.  If your environment is not
properly configured, or if you are planning on using wsdl2java,
javac, and java to build and run the demos, you must set the
environment.


Building and running the demo using Maven
-----------------------------------------

From the base directory of this sample (i.e., where this README file is
located), the pom.xml file is used to build and run the demo.

Using either UNIX or Windows:

  ./mvnw install   (builds the demo)
  ./mvnw -Pserver  (from one command line window)
  ./mvnw -Pclient  (from a second command line window)


To remove the code generated from the WSDL file and the .class
files, run "mvn clean".


