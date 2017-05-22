# javaee-example
[![Coverage Status](https://coveralls.io/repos/github/NekoStark/javaee-example/badge.svg?branch=master)](https://coveralls.io/github/NekoStark/javaee-example?branch=master)
[![Build Status](https://travis-ci.org/NekoStark/javaee-example.svg?branch=master)](https://travis-ci.org/NekoStark/javaee-example)

An example of full-stack JavaEE Application with JPA, CDI and JSF

**This is just a test**, not to be taken as a template for production projects



### Installation

Create the war file using Maven (with **mvn clean package** or from Eclipse)

Run on **Wildfly Server 10.1.0.Final**.

To add some user and notes to the database, uncomment the following annotations
```Java
package it.unifi.ing.stlab.swa.bean.startup;

@Singleton
@Startup
public class StartupBean {
  ...
}
```
