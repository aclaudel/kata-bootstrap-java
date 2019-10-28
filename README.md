# kata-bootstrap-java
Maven archetype to quickly generate a pom for TDD katas.

The pom will have the following dependencies added to the pom:
- Junit 5
- Mockito
- Hamcrest matchers
- Google Guava
- Lombok

A test class will be generated with some examples for each libraries.

# Installation

The archetype is not available on a public repository, therefore you'll need to install it in your local repository.

Simply clone the project and run `mvn clean install`.

# Usage

You can use this archetype when creating a new maven project in your IDE.

## IntelliJ IDEA

*New > Project.. > Maven > Create from archetype > Add Archetype...*.

- GroupId: aclaudel.kata
- ArtifactId: kata-bootstrap
- Version: 1.0

Then click *Next* and generate your project.
