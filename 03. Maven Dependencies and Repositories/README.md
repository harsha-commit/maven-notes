# Section 3 - Maven Dependencies and Repositories

## The pom.xml file

- contains information about the project and configuration details used to build the project
- contains default values for most projects

## Types of Dependency

- There are two types of Maven dependencies:
	- **Direct:** These are dependencies defined in your `pom.xml` file under the `<dependencies/>`section
	- **Transitive:** These are dependencies that are dependencies of your direct dependencies

## Maven Repositories

- Local Repository
	- When a maven project is run for the first time, the local repository is created
	- Created inside User's Home directory with name as .m2
	- Stores packages, dependencies and much more
- Maven Central Repository
	- official repository of Maven
- Enterprise Repository
	- enterprises can create their own private repository


