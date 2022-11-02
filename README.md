# Introduction to Spring

## Learning Goals

- Explain what an application framework is and how it can be beneficial.
- Discuss the advantages to using Spring.

## What is an Application Framework?

An **application framework** provides a set of functionalities which we can use
to build an application. They provide several features that developers can use.
Depending on the application, the developers can decide which specific features
to use on their projects.

We can think of an application framework like this: Consider a set of classic
LEGO bricks. The set comes with several different types of pieces to build
whatever we may want along with some suggestions of what to possibly create.
All the building blocks are available, but it is up to us, the developers, to
choose which pieces we want to use. Maybe we want to use the LEGOs to build a
castle, but another project wants to use the LEGO pieces to build a city. We get
to select which features to implement when assembling our LEGO creation.

An application framework works the same way. The framework provides us all the
features we could want to create our application. It is up to us, the
developers, to choose the appropriate software capabilities from the framework
to build our application. Some components a framework might offer are
abstractions for capabilities like security, logging, caching, and other
utilities that may be common across various applications.

## Why Use an Application Framework?

So far, we have been building Java programs without an application framework and
have been holding our own just fine. So why do we need an application framework?

Reuse, reuse, reuse!

They always say to not reinvent the wheel and this is a case for that saying.
Since application frameworks already come with built-in features for us to
pick and choose from, we can just reuse code and capabilities that already exist
and have been tested by others. There is also a community support of other
programmers using these built-in features where we can seek help and support if
needed. As we build more complex programs, the more we can take advantage of
these features offered by application frameworks, cutting down our costs, and
allowing us to just focus on writing the business logic.

## What is Spring?

Spring is one of the most popular Java application frameworks in the world. It
will allow us to build an application using "Plain Old Java Objects" or POJOs
while taking advantage of some popular features in the Spring framework. Spring
is a collection of sub-frameworks, or modules. This introduces us to the concept
of the **Spring ecosystem**. Here are some of the software capabilities that
are included in the Spring framework:

- **Spring Core**: provides the foundational mechanisms for integrating Spring
  into applications. The Spring core is based on the _Inversion of Control_
  principle. Instead of defining exactly how an application is controlled,
  (instance creation, calling methods, etc.) we define configurations which
  instruct Spring on how to manage code.
- **Spring Model-View Controller (MVC)**: allows programmers to develop web
  applications.
- **Spring Data Access**: supports connecting an application to a database
  (like PostgreSQL) to abstract the process of data persistence.
- **Spring Testing**: allows developers to write tests for a Spring application.

For more information on the Spring modules included in the Spring framework,
checkout out the
[Introduction to Spring Framework](https://docs.spring.io/spring-framework/docs/4.0.x/spring-framework-reference/html/overview.html).

## What is Spring Boot?

As Spring grew in popularity and its ecosystem evolved, Spring introduced the
concept of **Spring projects**. These projects were developed on top of the
existing Spring framework to enhance certain functionalities. Here is a list of
some Spring projects worth mentioning:

- Spring Boot
- Spring Cloud
- Spring Security
- Spring Batch
- Spring Mobile

For a full list of projects, see [Spring Projects](https://spring.io/projects).

Within this module, we will focus mainly on Spring Boot.

A Spring application requires lots of configuration. **Spring Boot** is a
project under Spring which takes care of most of the configurations so that
developers can focus on the business logic of their application. Here are some
of the benefits of Spring Boot:

- Easy project creation: initialization services like
  [Spring Initializr](https://start.spring.io/) provide skeleton applications
  with base configurations.
- Dependency Starters: there are bundled dependencies for specific types of
  applications.
- Dependency based autoconfiguration: default configurations are defined based
  on the dependencies added to the project.
- Application health/metrics monitoring.
- Embedded application server.

## Conclusion

We have learned about Spring, some of its modules, and Spring Boot in this
lesson. Spring is an application framework that makes application management
easier and Spring Boot is a subproject of Spring which streamlines most
configurations. In the coming lessons, we will learn more about both Spring and
Spring Boot.

## References

- [Spring Framework Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/index.html)
  (reference document)
- [Introduction to Spring Framework](https://docs.spring.io/spring-framework/docs/4.0.x/spring-framework-reference/html/overview.html)
- [Spring Projects](https://spring.io/projects)
- [Spring Guides](https://spring.io/guides)
