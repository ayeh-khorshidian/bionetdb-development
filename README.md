# BioNetDB

BioNetDB implements a storage engine to work with biological networks using a NoSQL graph database. BioNetDB integrates relevant biological networks information from well-known data sources such as Reactome. All this data can be queried through command line interface.


##### Contributing
BioNetDB is an open-source and collaborative project. We appreciate any help and feedback from users, you can contribute in many different ways such as simple bug reporting and feature request. Depending on your skills you are more than welcome to develop client tools, new features or even fixing bugs.

# How to build 
BioNetDB is mainly developed in Java and it uses [Apache Maven](http://maven.apache.org/) as building tool. BioNetDB requires Java 8+ and others OpenCB Java dependencies that can be found in [Maven Central Repository](http://search.maven.org/).

Stable releases are merged and tagged at **_master_** branch. You are encouraged to use latest stable release for production. Current active development is carried out at **_develop_** branch, only compilation is guaranteed and bugs are expected, use this branch for development or for testing new functionalities. Only dependencies of **_master_** branch are ensured to be deployed at [Maven Central Repository](http://search.maven.org/), **_develop_** branch may require users to download and install other active OpenCB repositories:

