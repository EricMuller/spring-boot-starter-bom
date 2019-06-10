# spring-boot-starter-bom


[![Build Status](https://travis-ci.com/EricMuller/spring-boot-starter-bom.svg?branch=1.5.9-SNAPSHOT)](https://travis-ci.com/EricMuller/qcm-rest-api) [![Known Vulnerabilities](https://snyk.io/test/github/EricMuller/spring-boot-starter-bom/badge.svg)](https://snyk.io/test/github/EricMuller/spring-boot-starter-bom)


spring-boot-starter-bom is a SpringBoot 1.5.x BOM.


###  What is Maven BOM?

BOM stands for Bill Of Materials. A BOM is a special kind of POM that is used to control the versions of a project’s dependencies and provide a central place to define and update those versions.

BOM provides the flexibility to add a dependency to our module without worrying about the version that we should depend on.


### Tech

spring-boot-starter-bom configures a number of open source projects:

* [SpringBoot] - Create stand-alone backend Spring applications
* [Spring Data JPA]  - provides repository support for the Java Persistence API (JPA)
* [SpringFoxSwagger] - Automated JSON API documentation for API's built with Spring
* [JOOQ] - jOOQ generates Java code from your database and lets you build type safe SQL queries through its fluent API.
* [MapStruct] - code generator that greatly simplifies the implementation of mappings between Java bean types  
* [keycloak] - an open source identity and access management solution
* [Lombok] - Never write another getter or equals method again
* [Maven] - the build system
* [Travis] - Test and Deploy with Confidence [![N|Solid](https://cdn.travis-ci.org/images/favicon-076a22660830dc325cc8ed70e7146a59.png)](https://travis-ci.org/)
* [Snyk] - Finding & fixing vulnerabilities in your dependencies
* [Heroku] - Fully managed container-based cloud platform, with integrated data services.
* [JaCoCo] - JaCoCo is a free code coverage library for Java,.
* [SonarQube] - SonarQube is an open-source platform for continuous inspection of code quality.

### Deploy 

```sh
$ cd spring-boot-starter-bom
$ maven install deploy -X
```

License
----
[![License](http://img.shields.io/:license-mit-blue.svg)](https://opensource.org/licenses/mit-license.php)



Code is under the [MIT Licence ](https://opensource.org/licenses/mit-license.php).
